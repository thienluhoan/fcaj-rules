# FCAJ Internship Regulations & Handbook (fcaj-rules)

Trang tài liệu tra cứu nội quy, hướng dẫn thủ tục, quy định thực tập và barem chấm điểm dành cho sinh viên thực tập tại **First Cloud AI Journey (FCAJ)**.

- **Website chính thức:** [https://hcm-rules.awsfcaj.com](https://hcm-rules.awsfcaj.com)
- **Engine:** [Hugo](https://gohugo.io/) (Extended)
- **Theme:** [hugo-theme-learn](https://github.com/matcornic/hugo-theme-learn)

---

## 1. Yêu cầu hệ thống (Prerequisites)

- **Hugo Extended**: Phiên bản `v0.134.3` trở lên (bắt buộc dùng bản **Extended** để hỗ trợ biên dịch SCSS/SASS và các module liên quan).
  - Kiểm tra phiên bản bằng lệnh:
    ```bash
    hugo version
    ```
    *(Output phải có chữ `+extended`, ví dụ: `hugo v0.149.1...+extended`)*
  - Cài đặt Hugo Extended:
    - **Windows (Chocolatey):** `choco install hugo-extended -confirm`
    - **Windows (Scoop):** `scoop install hugo-extended`
    - **Windows (Winget):** `winget install Hugo.Hugo.Extended`
    - **macOS (Homebrew):** `brew install hugo`
- **Git**: Đã cài đặt Git trên máy.

---

## 2. Cài đặt & Chuẩn bị Repository

### Clone repository kèm Theme submodule:
```bash
git clone --recurse-submodules <URL_REPOSITORY>
cd fcaj-rules
```

Nếu bạn đã clone dự án trước đó nhưng chưa tải theme:
```bash
git submodule update --init --recursive
```

---

## 3. Lệnh CLI chạy môi trường Local (Local Development)

### Khởi động Development Server:
```bash
# Lệnh chạy cơ bản
hugo server
```

### Các tuỳ chọn nâng cao khi chạy local:
```bash
# Hiển thị cả các bài viết nháp (drafts) và cập nhật thay đổi trực tiếp (live reload)
hugo server -D

# Chỉ định port và bind IP rõ ràng (tránh xung đột mạng)
hugo server --port 1313 --bind 127.0.0.1

# Điều hướng Base URL về localhost để không bị redirect về domain thật
hugo server -D --baseURL http://localhost:1313/
```

Sau khi chạy lệnh, mở trình duyệt và truy cập:
👉 **[http://localhost:1313](http://localhost:1313)**

---

## 4. Lệnh Build cho Production (Production Build)

Khi cần đóng gói website tĩnh (sẽ xuất toàn bộ output ra thư mục `./public`):

```bash
hugo --minify
```

---

## 5. Cấu trúc thư mục (Project Structure)

```text
fcaj-rules/
├── .github/workflows/
│   └── hugo.yml         # GitHub Actions tự động build & deploy lên gh-pages
├── archetypes/          # Mẫu tạo trang nội dung mới
├── config.toml          # File cấu hình chính của Hugo (metadata, menu, languages)
├── content/             # Toàn bộ nội dung tài liệu (Markdown)
│   ├── _index.md        # Trang chủ
│   ├── 1-regulations/   # 1. Nội quy (Chuyên cần, thời gian, trang phục, ra vào...)
│   ├── 2-instructions/  # 2. Hướng dẫn (Portal, điểm danh, nộp workshop, mua áo...)
│   ├── 3-project/       # 3. Quy định làm Project & Workshop
│   ├── 4-violations/    # 4. Xử lý vi phạm & cơ cấu điểm
│   └── 5-scoring/       # 5. Barem chấm điểm
├── layouts/             # Giao diện tùy biến (custom layouts / overrides)
├── static/              # Tài nguyên tĩnh
│   ├── css/             # Custom CSS
│   ├── fonts/           # Web fonts
│   └── images/          # Hình ảnh minh họa & hướng dẫn
└── themes/
    └── hugo-theme-learn # Git submodule giao diện Learn theme
```

---

## 6. Quy ước viết bài & Shortcodes hữu ích

Hugo Learn theme hỗ trợ các shortcode thông báo (Notices) nổi bật:

```markdown
{{% notice info %}}
Thông tin cần lưu ý hoặc hướng dẫn thêm.
{{% /notice %}}

{{% notice note %}}
Ghi chú quan trọng.
{{% /notice %}}

{{% notice warning %}}
Cảnh báo vi phạm hoặc điều khoản bắt buộc.
{{% /notice %}}
```

---

## 7. Quy trình CI/CD & Deploy

- Dự án sử dụng **GitHub Actions** (`.github/workflows/hugo.yml`).
- Khi có thay đổi được push hoặc merge vào nhánh `v2`, workflow sẽ tự động chạy:
  1. Setup Hugo Extended phiên bản tương thích.
  2. Chạy lệnh `hugo --minify`.
  3. Deploy thư mục `./public` lên nhánh `gh-pages` để phát hành tại [https://hcm-rules.awsfcaj.com](https://hcm-rules.awsfcaj.com).
