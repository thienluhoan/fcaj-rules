---
title: "Tiêu chí chấm Workshop"
date: 2025-01-12
weight: 5
chapter: false
pre: " <b> 5. </b> "
---

Tài liệu này mô tả **barem tổng quan** và **các quy tắc / lưu ý quan trọng** trong quá trình đánh giá kết quả thực tập dành cho sinh viên tham gia chương trình First Cloud AI Journey (FCAJ). Sinh viên cần nắm vững các tiêu chuẩn và các trường hợp bị điểm liệt / trừ điểm để hoàn thành tốt kỳ thực tập.

---

### 1. Barem tổng quan

| Nhóm tiêu chí       | Điểm tối đa | Ghi chú                      |
| ------------------- | ----------- | ---------------------------- |
| Worklog / Blog      | **1.0**     |                              |
| Proposal / Workshop | **5.0**     | Architecture chiếm tỷ lệ cao |
| Thái độ / tác phong | **2.0**     |                              |
| Chuyên cần          | **1.5**     |                              |
| Bonus               | **0.5**     | Chỉ cộng khi đủ điều kiện    |
| **TỔNG**            | **10.0**    |                              |

{{% notice info %}}
Yêu cầu điểm tổng kết **tối thiểu 7.0/10** để được xét chứng nhận hoàn thành thực tập.
{{% /notice %}}

---

### 2. Các quy định & Lưu ý quan trọng theo từng nhóm tiêu chí

#### 2.1. Worklog / Blog – 1.0 điểm

Nhóm tiêu chí này đánh giá thói quen học tập, đúc kết kiến thức và tính kỷ luật của sinh viên thông qua việc viết Blog kỹ thuật và ghi nhận nhật ký làm việc (Daily Worklog).

- **Blog kỹ thuật:** Yêu cầu tối thiểu **3 bài Blog** chất lượng chia sẻ về các chủ đề/công nghệ đã học hoặc nghiên cứu trong kỳ thực tập.
- **Daily Worklog:** Ghi nhận đều đặn tiến độ hàng ngày, thể hiện rõ công việc và nội dung đã học/làm theo đúng template quy định, kèm trích dẫn tài liệu tham khảo (references).

{{% notice warning %}}
**ĐIỀU KIỆN TIÊN QUYẾT:**
- Bắt buộc phải có cả **Blog** VÀ **Daily Worklog**. Nếu thiếu 1 trong 2 nội dung này thì toàn bộ nhóm Worklog = **0 điểm**.
- Không ghi nhận nhật ký, viết qua loa không đúng template hoặc thiếu bài viết kỹ thuật sẽ bị trừ điểm theo quy định.
{{% /notice %}}

---

#### 2.2. Proposal / Workshop – 5.0 điểm

Đây là phần chiếm trọng số lớn nhất trong kỳ thực tập, đánh giá năng lực chuyên môn và giải pháp kỹ thuật của sinh viên. 

Cấu phần gồm: Thiết kế kiến trúc (**Architecture**), Bản chạy thực tế (**Demo**) và **Trình bày giải pháp** (Proposal/Workshop).

{{% notice warning %}}
**QUY TẮC KHÓA WORKSHOP (ĐIỂM LIỆT):**
- Không có Architecture **HOẶC** không trình bày Workshop/Proposal thì toàn bộ điểm Workshop = **0 điểm** (1 trong 2 không có).
{{% /notice %}}

**Các lưu ý quan trọng về chuyên môn:**

- **Kiến trúc hệ thống (Architecture):**
  - Phải tuân thủ chuẩn thiết kế của AWS (đúng icon, đúng tên dịch vụ, kết nối và luồng dữ liệu hợp lý).
  - Áp dụng các nguyên tắc của **AWS Well-Architected Framework** (Security, Reliability, Performance Efficiency, Cost Optimization, Operational Excellence). Trong đó, khía cạnh **Security** luôn được đánh giá rất nghiêm ngặt.
  - Sinh viên phải tự vẽ, tự thiết kế và giải thích cặn kẽ giải pháp của mình. Giải pháp thực tế (workshop) **phải thể hiện được đúng như những gì đã thiết kế trên Architecture**.

{{% notice warning %}}
**QUY TẮC VỀ GENAI TRONG ARCHITECTURE:**
- Architecture **hoàn toàn do AI tạo** = **0 điểm**.
- Trường hợp có dùng AI hỗ trợ nhưng không chỉnh sửa kỹ lưỡng, để sót các lỗi cơ bản (sai icon, sai tên service, luồng vô lý, chồng chéo...) sẽ bị trừ điểm rất nặng.
- Nếu vẽ không đúng chuẩn AWS nhưng là công sức tự tay thiết kế thì chỉ được ghi nhận điểm tối thiểu cho công vẽ.
{{% /notice %}}

- **Demo sản phẩm:**
  - Bắt buộc phải có sản phẩm chạy thực tế (Live demo, video minh chứng rõ ràng hoặc link production hoạt động). Không có demo/sản phẩm = **0 điểm Demo**.
- **Trình bày (Proposal & Workshop):**
  - Trình bày mạch lạc, rõ ràng, thể hiện đầy đủ bài toán và cách giải quyết.
  - **Bắt buộc phải có phần dự toán và tối ưu chi phí (COST):** Báo cáo hoặc bài thuyết trình **thiếu phần COST = 0 điểm mục Trình bày**.

---

#### 2.3. Thái độ / tác phong – 2.0 điểm

Đánh giá tính chuyên nghiệp, văn hóa làm việc và sự tuân thủ kỷ luật của sinh viên trong môi trường doanh nghiệp.

- **Thái độ:** Tinh thần cầu thị, chủ động trong công việc, lịch sự, tôn trọng mọi người và đặc biệt là tính trung thực.
- **Tuân thủ nội quy:** Chấp hành nghiêm chỉnh giờ giấc, văn hóa văn phòng, trang phục và các quy định của chương trình.

{{% notice warning %}}
**CÁC LỖI VI PHẠM ĐẶC BIỆT NGHIÊM TRỌNG:**
- **Gian dối / không trung thực:** Cố tình khai báo sai, gian lận thông tin hoặc chối bỏ vi phạm rõ ràng = **0 điểm mục Thái độ**.
- **Hút thuốc tại văn phòng:** Nhận ngay **0 điểm cho cả 2 mục** (Thái độ = 0 và Tuân thủ nội quy = 0), đồng thời chịu hình thức kỷ luật.
- **Tự ý bỏ về / vắng không phép:** Bị đánh giá **0 điểm mục Tuân thủ nội quy**.
- Các vi phạm khác (đi trễ, làm việc riêng, vi phạm trang phục...) sẽ bị trừ điểm trực tiếp theo quy định tại [4. Xử lý vi phạm](../4-violations/).
{{% /notice %}}

---

#### 2.4. Chuyên cần – 1.5 điểm

Đánh giá sự hiện diện và mức độ tích cực tham gia các hoạt động thực tế của chương trình.

- **Lên văn phòng (Office):** Đảm bảo đủ số buổi làm việc tại văn phòng theo quy định (tối thiểu 10 buổi hoặc số lượt booking hợp lệ). Thiếu buổi sẽ bị trừ điểm tương ứng.
- **Tham gia sự kiện (Event):** Tham gia đủ tối thiểu **3 sự kiện** chuyên môn / cộng đồng theo thông báo của ban tổ chức.

{{% notice warning %}}
**LƯU Ý VỀ MINH CHỨNG CHUYÊN CẦN:**
- Khi tham gia các sự kiện (Event), sinh viên **bắt buộc phải chụp ảnh check-in rõ mặt, hợp lệ** và đính kèm vào báo cáo.
- Sự kiện thiếu ảnh hoặc ảnh không rõ ràng/không hợp lệ sẽ không được tính đủ điểm. Thiếu event sẽ bị trừ điểm trực tiếp vào điểm chuyên cần.
{{% /notice %}}

---

#### 2.5. Điểm thưởng (Bonus – 0.5 điểm)

Chỉ dành cho những sinh viên thể hiện sự xuất sắc và kỷ luật toàn diện trong suốt kỳ thực tập.

{{% notice tip %}}
**ĐIỀU KIỆN ĐẠT ĐIỂM BONUS (+0.5 ĐIỂM):**
Sinh viên chỉ được cộng điểm thưởng khi **thỏa mãn đồng thời cả 3 điều kiện**:
1. Đạt điểm tối đa nhóm **Thái độ / tác phong (2.0/2.0)**.
2. Đạt điểm tối đa nhóm **Chuyên cần (1.5/1.5)**.
3. Hoàn thành đầy đủ và chất lượng **Workshop/Project** (đầy đủ Architecture, Demo hoạt động và Trình bày giải pháp).
{{% /notice %}}

---

**Liên quan:** [3. Quy định về project](../3-project/) · [4. Xử lý vi phạm](../4-violations/) · [1.1. Chuyên cần](../1-regulations/1.1-diligence/)
