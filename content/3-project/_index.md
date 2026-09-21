---
title: "Quy định về Workshop"
date: 2025-01-12
weight: 3
chapter: false
pre: " <b> 3. </b> "
---

{{% notice note %}}
**Thời gian nộp Workshop:** 15 ngày trước ngày cần mộc để nộp về trường.
{{% /notice %}}

### 1. Hình thức và công cụ làm báo cáo

#### 1.1. Hình thức bắt buộc

* Workshop website: [Mẫu workshop](https://workshop-sample.awsfcaj.com/)
* Template: [FCAJ-workshop-template](https://github.com/thienluhoan/fcj-workshop-template) trên GitHub (Dựa trên template này, hãy làm 1 bản riêng biệt dành cho bản thân)

#### 1.2. Yêu cầu bắt buộc

* Có **đầy đủ 2 ngôn ngữ (vi / en)** cho toàn bộ nội dung chính
* Cấu trúc rõ ràng theo các mục đã nêu:
  * Hình ảnh minh họa chất lượng cao
  * Sơ đồ kiến trúc (Architecture diagram chuẩn AWS)
  * Code snippet / Script triển khai
  * File đính kèm (CloudFormation, Dockerfile, Terraform, script, …) nếu có
* Hãy tham khảo từ **Workshop mẫu** (link tại phần 1.1) để làm đúng cấu trúc chuẩn

{{% notice warning %}}
Đặc biệt, phần 5. Workshop: **Workshop phải tự triển khai, tự thực hiện như một sản phẩm cá nhân và viết thành tài liệu cho mục này**, tuyệt đối không sao chép y nguyên Workshop mẫu.
{{% /notice %}}

---

### 2. Nội dung bắt buộc của báo cáo / template

**Báo cáo Workshop** cuối khóa **phải được viết bằng 2 ngôn ngữ: tiếng Anh và tiếng Việt** (tham khảo link template tại phần 1.1).

### Các phần tối thiểu cần có trong báo cáo / template

#### 2.1. Thông tin sinh viên

* Họ tên
* Số điện thoại
* Email
* Trường
* Chuyên ngành
* Công ty thực tập
* Vị trí thực tập
* Thời gian thực tập

#### 2.2. Worklog (Nhật ký theo tuần / ngày)

* Ghi nhận đầy đủ từ **Week 1 → Week 12**
* Mỗi tuần mô tả:
  * Công việc đã làm
  * Kết quả đạt được
  * Tài liệu tham khảo (References)
* Bắt buộc duy trì Daily Worklog đều đặn kèm trích dẫn tài liệu theo quy định

#### 2.3. Proposal (Đề xuất giải pháp Workshop)

* Tổng quan bài toán / giải pháp
* Mục tiêu & phạm vi
* Vấn đề cần giải quyết
* Kiến trúc giải pháp sơ bộ
* Kế hoạch & Timeline thực hiện
* Bảng dự toán ngân sách & chi phí (Cost Estimation)
* Rủi ro & phương án giảm thiểu

> Ví dụ: **IoT Weather Platform trên AWS**

#### 2.4. Blogs Post

Mỗi cá nhân cần nghiên cứu hoặc chia sẻ về những kiến thức mình đã học được thành **tối thiểu 3 bài blogs**, sau đó đăng lên nhóm cộng đồng [AWS Study Group](https://www.facebook.com/groups/awsstudygroupfcj). Ví dụ:

* Giới thiệu & phân tích tính năng mới của các AWS services
* Chiến lược tối ưu chi phí (Cost Optimization) trên AWS
* Hướng dẫn giải quyết bài toán thực tế bằng dịch vụ AWS,...

#### 2.5. Events Participated

Tham gia **tối thiểu 3 sự kiện** chuyên môn / cộng đồng theo quy định. Mỗi sự kiện (Event 1, Event 2, Event 3, …) cần có:

* Tên sự kiện
* Thời gian
* Địa điểm
* Vai trò tham gia
* Nội dung chính tiếp thu
* **Hình ảnh check-in rõ mặt** chứng minh tham gia
* Bài học rút ra / đóng góp cá nhân

#### 2.6. Workshop (Nội dung kỹ thuật chính)

* Overview (Tổng quan về Workshop)
* Prerequisite (Điều kiện tiên quyết: tài khoản, công cụ, quyền hạn)
* Mô tả kiến trúc chi tiết (Architecture & Data Flow)
* Các bước triển khai thực hành (Step-by-step Lab Guide)
* Kiểm thử & đo lường (Testing & Validation qua Logs, Metrics, Alerts)
* Dọn dẹp tài nguyên (Clean-up)
* Minh chứng sản phẩm chạy thực tế (Demo link / Video)

#### 2.7. Self-evaluation (Tự đánh giá)

Tự đánh giá theo các tiêu chí sau, mỗi tiêu chí chọn **Tốt / Khá / Trung bình** kèm nhận xét cụ thể:

* Kiến thức chuyên môn
* Khả năng tự học & nghiên cứu
* Tính chủ động trong công việc
* Kỷ luật & tuân thủ quy định
* Kỹ năng giao tiếp
* Làm việc nhóm (Teamwork)
* Năng lực giải quyết vấn đề
* Đóng góp cho Workshop

#### 2.8. Sharing and Feedback

* Cảm nhận về chương trình thực tập FCAJ
* Mức độ hài lòng
* Những điểm cần cải thiện
* Có giới thiệu chương trình cho bạn bè không? Vì sao?

---

### 3. Yêu cầu đối với Workshop kỹ thuật

Workshop nên:

* Là **use-case thực tế trên AWS**:
  * Serverless application
  * Data pipeline / Analytics
  * Monitoring & Observability system
  * IoT & Event-driven platform
  * Containerized / Microservices architecture
  * …
* Sử dụng **ít nhất 3 dịch vụ AWS**

#### 3.1. Các yếu tố bắt buộc phải có để nhận được mộc thực tập (nếu cần)

Nếu bạn có nhu cầu nhận **mộc thực tập** của chương trình, bạn cần phải đáp ứng đầy đủ tất cả các yếu tố sau:

* Hoàn thành Workshop cá nhân đạt chuẩn
* Hoàn thành đầy đủ báo cáo theo template (link template tại phần 1.1)
* Thời gian thực tập tối thiểu 3 tháng
* Lên văn phòng đủ tối thiểu 10 buổi (hoặc số lượt booking hợp lệ)
* Tham gia đủ tối thiểu 3 sự kiện (Event) có đính kèm ảnh check-in rõ mặt hợp lệ
* Đăng đủ tối thiểu 3 bài blogs chất lượng lên nhóm [AWS Study Group](https://www.facebook.com/groups/awsstudygroupfcj)

#### 3.2. Workshop cần thể hiện được

* **Thiết kế kiến trúc chuẩn mực:**
  * Sơ đồ kiến trúc rõ ràng, đúng chuẩn AWS
  * Liệt kê đầy đủ các dịch vụ sử dụng và nêu rõ lý do lựa chọn
  * Tuân thủ các nguyên tắc thiết kế AWS Well-Architected Framework
* **Triển khai end-to-end (Reproducible):**
  * Hướng dẫn từng bước chi tiết, người khác có thể tự làm theo và triển khai thành công
* **Minh chứng demo thực tế:**
  * Có sản phẩm chạy thực tế (Live demo, video minh chứng rõ ràng hoặc link production hoạt động)
* **Kiểm thử & đo lường:**
  * Giám sát hệ thống qua Log, Metric, Alert (Amazon CloudWatch, Alarms...)
* **Dự toán & tối ưu chi phí:**
  * Bảng dự toán chi phí chi tiết bằng AWS Pricing Calculator
  * Giải pháp tối ưu chi phí trong vận hành
  * Hướng dẫn dọn dẹp tài nguyên (Clean-up) triệt để sau khi kết thúc lab

---

### 4. Tiêu chuẩn cho Workshop

{{% notice info %}}
Dưới đây là **Khung tiêu chuẩn Best Practices** giúp sinh viên định hướng, rà soát và xây dựng Workshop đạt chất lượng cao nhất theo đúng chuẩn mực của AWS và chương trình FCAJ.
{{% /notice %}}

#### 4.1. Ý tưởng & Mục tiêu bài toán (Problem Statement & Scope)

* **Bối cảnh & Bài toán thực tế:**
  * Hệ thống được xây dựng nhằm giải quyết vấn đề gì trong thực tế?
  * Đối tượng sử dụng / khách hàng mục tiêu là ai?
  * Ví dụ: Hệ thống thu thập và giám sát dữ liệu IoT thời gian thực, Pipeline xử lý dữ liệu tự động, Hệ thống logging & alert tập trung cho Microservices,...
* **Mục tiêu cụ thể & Tiêu chí hoàn thành:**
  * Đầu ra mong muốn rõ ràng: Dashboard trực quan, RESTful API hoạt động, hệ thống cảnh báo tự động gửi email/Slack khi có sự cố,...
  * Tiêu chí đo lường sự thành công của giải pháp.
* **Phù hợp định hướng Cloud & AWS:**
  * Đề tài gắn liền với hệ sinh thái AWS, tập trung khai thác các dịch vụ Cloud hiện đại, tránh đề tài lệch chủ đề hoặc mang tính chất lý thuyết đơn thuần.

#### 4.2. Kiến trúc & Thiết kế kỹ thuật (Architecture & Well-Architected Best Practices)

* **Sơ đồ kiến trúc (Architecture Diagram):**
  * Sơ đồ trực quan, thẩm mỹ, vẽ bằng các công cụ chuyên nghiệp (draw.io, Excalidraw, Lucidchart, Figma,...).
  * Sử dụng **bộ icon chính thức của AWS** (AWS Architecture Icons mới nhất), ghi đúng tên dịch vụ và thể hiện rõ luồng dữ liệu giữa các thành phần.
  * *Lưu ý quan trọng:* Sinh viên phải **tự tay thiết kế và hiểu cặn kẽ** kiến trúc của mình. Không sử dụng sơ đồ do GenAI tạo 100% (xem quy tắc khóa điểm tại [5. Tiêu chí chấm Workshop](../5-scoring/)).
* **Lựa chọn dịch vụ:**
  * Giải thích rõ căn cứ lựa chọn các dịch vụ (S3, Lambda, API Gateway, DynamoDB, SQS, ECS,...): dựa trên tiêu chí chi phí, tính sẵn sàng cao (High Availability), mô hình Serverless hay Managed Services.
* **Bảo mật & Quản lý danh tính (Security Pillar - Tiêu chí trọng tâm):**
  * Thiết lập IAM Role, IAM Policy tuân thủ nghiêm ngặt nguyên tắc **Least Privilege** (quyền tối thiểu cần thiết).
  * Hạn chế tối đa public tài nguyên ra Internet (đặt tài nguyên trong Private Subnet, sử dụng VPC Endpoint, cấu hình Security Group chặt chẽ).
  * **Tuyệt đối không hard-code credentials** (Access Key, Secret Key, token, mật khẩu cơ sở dữ liệu) trong code, file cấu hình hoặc GitHub repository.
* **Độ tin cậy & Vận hành (Reliability & Operational Excellence):**
  * Thiết kế có tính chịu lỗi, khả năng mở rộng (Auto Scaling, kiến trúc hướng sự kiện Event-driven, hàng đợi SQS giải phóng tải).
  * Thiết lập cơ chế giám sát, logging và cảnh báo tự động (CloudWatch Logs, Metrics, Alarms).

#### 4.3. Dự toán & Tối ưu chi phí (Cost Estimation & Optimization)

{{% notice warning %}}
**BẮT BUỘC:** Theo tiêu chí chấm Workshop, báo cáo hoặc bài trình bày **thiếu phần COST sẽ nhận 0 điểm mục Trình bày**.
{{% /notice %}}

* **Bảng dự toán chi phí (Cost Estimation):**
  * Xây dựng bảng dự toán chi phí chi tiết bằng công cụ **[AWS Pricing Calculator](https://calculator.aws/)**.
  * Dự toán dựa trên kịch bản tải thực tế (lưu lượng request, dung lượng lưu trữ, băng thông mạng).
* **Chiến lược tối ưu chi phí (Cost Optimization):**
  * Đề xuất các phương án tối ưu: tận dụng AWS Free Tier, ưu tiên kiến trúc Serverless trả tiền theo lượt sử dụng, thiết lập vòng đời dữ liệu (S3 Lifecycle Policy), lựa chọn dung lượng và compute tier phù hợp.
* **Quy trình dọn dẹp tài nguyên (Clean-up):**
  * Cung cấp các bước hướng dẫn dọn dẹp chi tiết sau khi thực hành xong (xóa stack, empty và xóa S3 bucket, tắt alarm, giải phóng Elastic IP...) để tránh phát sinh chi phí ngoài ý muốn trên tài khoản AWS.

#### 4.4. Hướng dẫn thực hành Step-by-Step & Demo sản phẩm

* **Điều kiện tiên quyết (Prerequisites):**
  * Nêu rõ các yêu cầu trước khi thực hành: tài khoản AWS, Region khuyến nghị, quyền IAM cần thiết.
  * Các công cụ cần cài đặt và cấu hình: AWS CLI, Git, Docker, SAM, CDK hoặc Terraform (nếu áp dụng).
* **Hướng dẫn từng bước chi tiết (Step-by-step Lab Guide):**
  * Phân chia thành từng bước rõ ràng, logic (Step 1: Khởi tạo mạng VPC -> Step 2: Cấu hình IAM Role -> Step 3: Triển khai backend -> ...).
  * Cung cấp đầy đủ câu lệnh CLI, cấu hình file mẫu, screenshot hướng dẫn trực quan trên AWS Management Console.
  * Đảm bảo tính **tái lập (Reproducible)**: người đọc hoàn toàn có thể tự làm theo từ đầu đến cuối mà không gặp lỗi đứt gãy.
* **Kiểm thử & Xác thực (Testing & Validation):**
  * Hướng dẫn cụ thể cách gửi request test (qua cURL, Postman hoặc giao diện Web).
  * Hướng dẫn kiểm tra kết quả thực tế qua log CloudWatch, kiểm tra dữ liệu được ghi nhận trong cơ sở dữ liệu.
  * Kiểm thử các kịch bản lỗi (ví dụ: request sai định dạng, quá tải) để xem hệ thống xử lý ra sao.
* **Sản phẩm chạy thực tế (Live Demo / Video Minh chứng):**
  * Bắt buộc phải có sản phẩm hoạt động thực tế: cung cấp đường link demo trực tiếp, video quay lại quá trình hoạt động thực tế hoặc link production. *(Không có demo sản phẩm = 0 điểm mục Demo)*.

#### 4.5. Tài liệu hóa & Trình bày (Documentation & Formatting)

* **Chuẩn song ngữ (Bilingual vi / en):**
  * Bắt buộc có cả hai phiên bản tiếng Việt và tiếng Anh cho tất cả nội dung chính.
  * Văn phong chuyên nghiệp, dịch chuẩn xác thuật ngữ kỹ thuật điện toán đám mây.
* **Cấu trúc & Giao diện Website:**
  * Xây dựng dựa trên template tiêu chuẩn FCAJ, mục lục (Table of Contents) rõ ràng, navigation điều hướng thuận tiện.
* **Trình bày chuyên nghiệp:**
  * Font chữ, định dạng text dễ đọc, ngắt đoạn hợp lý.
  * Các đoạn mã nguồn (code snippet, CLI, policy JSON) phải đặt trong code block có syntax highlighting tương ứng.
  * Hình ảnh minh họa rõ nét, có chú thích đầy đủ, hạn chế lỗi chính tả.

#### 4.6. Đóng góp cá nhân & Đổi mới sáng tạo (Personal Contribution & Reflection)

* **Mức độ tự chủ & Tùy biến sáng tạo:**
  * Workshop phải là kết quả làm việc độc lập của sinh viên, thể hiện sự tìm tòi, sáng tạo riêng biệt.
  * Có sự mở rộng hoặc tùy biến so với các bài lab cơ bản: tích hợp thêm dịch vụ mới, tối ưu bảo mật sâu hơn, bổ sung tính năng tự động hóa (CI/CD, IaC).
* **Bài học kinh nghiệm & Xử lý sự cố (Troubleshooting & Reflection):**
  * Nêu rõ các khó khăn, lỗi kỹ thuật đã gặp phải trong quá trình triển khai và cách thức sinh viên đã tìm tòi giải quyết.
  * Định hướng phát triển, mở rộng giải pháp trong tương lai.

**Liên quan:** [5. Tiêu chí chấm Workshop](../5-scoring/)