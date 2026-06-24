---
title: "Quy định về project"
date: 2025-01-12
weight: 3
chapter: false
pre: " <b> 3. </b> "
---

### 1. Hình thức và công cụ làm báo cáo

#### 1.1. Hình thức bắt buộc

* Workshop website: [Mẫu workshop](https://workshop-sample.awsfcaj.com/)
* Template: [FCAJ-workshop-template](https://github.com/thienluhoan/fcj-workshop-template) trên GitHub (Dựa trên template này, hãy làm 1 bản riêng biệt dành cho bản thân)

#### 1.2. Yêu cầu bắt buộc

* Có **đầy đủ 2 ngôn ngữ (vi / en)** cho phần nội dung chính
* Cấu trúc rõ ràng theo các mục đã nêu:
  * Hình ảnh minh họa
  * Sơ đồ kiến trúc
  * Code snippet
  * File đính kèm (CloudFormation, Dockerfile, script, …) nếu phù hợp
* Hãy tham khảo từ **báo cáo mẫu** (link tại phần 1.1) để làm đúng cấu trúc

{{% notice warning %}}
Đặc biệt, phần 5. Workshop, **Workshop phải tự triển khai, tự làm như 1 dự án cá nhân và viết thành báo cáo cho mục này**, không copy y nguyên Workshop mẫu
{{% /notice %}}


---

### 2. Nội dung bắt buộc của báo cáo / template

**Báo cáo** cuối khóa **phải được viết bằng 2 ngôn ngữ: tiếng Anh và tiếng Việt**. (link tại phần 1.1)

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

#### 2.2. Worklog (Nhật ký theo tuần)

* Ghi rõ từ **Week 1 → Week 12**
* Mỗi tuần mô tả:

  * Công việc đã làm
  * Kết quả đạt được

#### 2.3. Proposal (Đề xuất dự án)

* Tổng quan dự án
* Mục tiêu
* Vấn đề cần giải quyết
* Kiến trúc giải pháp
* Timeline
* Ngân sách (nếu có)
* Rủi ro

> Ví dụ: **IoT Weather Platform trên AWS**

#### 2.4. Blogs Post

Mỗi nhóm cần phải nghiên cứu hoặc chia sẻ về những gì mình học được thành 3 bài blogs sau đó post lên [AWS Study Group](https://www.facebook.com/groups/awsstudygroupfcj), ví dụ:

* Tính năng mới của services
* Tối ưu chi phí bằng cách,...
* Sử dụng services để,...

#### 2.5. Events Participated

Mỗi event (Event 1, Event 2, …) cần có:

* Tên sự kiện
* Thời gian
* Địa điểm
* Vai trò
* Nội dung chính
* Hình ảnh hoặc video chứng minh tham gia
* Bài học rút ra / đóng góp cá nhân

#### 2.6. Workshop (Project kỹ thuật chính)

* Overview
* Prerequisite
* Mô tả kiến trúc
* Các bước thực hành (ví dụ):

  * Truy cập S3 từ VPC / on-prem
  * Cấu hình VPC Endpoint
  * IAM Policy
  * Test
  * Clean-up

#### 2.7. Self-evaluation (Tự đánh giá)

Đánh giá theo các tiêu chí sau, mỗi tiêu chí chọn **Tốt / Khá / Trung bình** và có nhận xét:

* Kiến thức
* Khả năng học hỏi
* Tính chủ động
* Kỷ luật
* Giao tiếp
* Teamwork
* Giải quyết vấn đề
* Đóng góp cho dự án

#### 2.8. Sharing and Feedback

* Cảm nhận về chương trình
* Mức độ hài lòng
* Điểm cần cải thiện
* Có giới thiệu chương trình cho bạn bè không? Vì sao?

---

### 3. Yêu cầu đối với Project kỹ thuật (Workshop)

Project nên:

* Là **use-case thực tế trên AWS**:

  * Serverless application
  * Data pipeline
  * Monitoring system
  * IoT
  * …
* Sử dụng **ít nhất 3 dịch vụ AWS**

#### 3.1. Các yếu tố bắt buộc phải có để nhận được mộc thực tập (nếu cần)

Nếu bạn có nhu cầu nhận **mộc thực tập** của chương trình, bạn cần phải có đủ tất cả yếu tố sau:

* Hoàn thành Project (dự án cá nhân)
* Hoàn thành báo cáo (link template tại phần 1.1)
* Thời gian thực tập ít nhất 3 tháng
* Lên văn phòng đủ 10 buổi
* Post đủ 3 bài blogs lên nhóm [AWS Study Group](https://www.facebook.com/groups/awsstudygroupfcj)

#### 3.2. Project cần thể hiện được

* Thiết kế kiến trúc:

  * Sơ đồ kiến trúc
  * Dịch vụ sử dụng
  * Lý do lựa chọn dịch vụ
* Triển khai end-to-end:

  * Các bước chi tiết
  * Người khác có thể làm theo
* Kiểm thử & đo lường:

  * Log
  * Metric
  * Alert
* Tối ưu:

  * Chi phí
  * Bảo mật cơ bản
  * Clean-up để tránh phát sinh chi phí

---

### 4. Thang điểm mẫu cho Project

#### 4.1. Ý tưởng & mục tiêu (1.0 điểm)

* **Bối cảnh & bài toán**:

  * Hệ thống dùng để làm gì?
  * Khách hàng là ai?
  * Giải quyết vấn đề gì?
  * Ví dụ: giám sát thời tiết, logging, monitoring microservice
* **Mục tiêu cụ thể**:

  * Output mong muốn (dashboard, API, alert, …)
  * Tiêu chí đánh giá thành công
* **Phù hợp chương trình**:

  * Use-case gắn với FCAJ / AWS
  * Không quá chung chung, không lệch chủ đề cloud

#### 4.2. Kiến trúc & thiết kế kỹ thuật (2.0 điểm)

* **Sơ đồ kiến trúc**:

  * Diagram rõ ràng (draw.io, PowerPoint, Excalidraw, …)
  * Thể hiện đầy đủ service AWS, luồng dữ liệu
* **Lựa chọn dịch vụ**:

  * Giải thích vì sao chọn S3 / Lambda / API Gateway / DynamoDB, …
  * Dựa trên chi phí, độ đơn giản, serverless, managed service
* **Bảo mật & IAM cơ bản**:

  * IAM Role
  * Principle of Least Privilege
  * Hạn chế public resource
  * Không hard-code access key
* **Khả năng mở rộng & vận hành**:

  * Scale: Auto Scaling, event-driven, SQS, …
  * Logging / Monitoring: CloudWatch, Alarm

#### 4.3. Triển khai & lab step-by-step (2.0 điểm)

* **Prerequisite**:

  * Tài khoản AWS
  * Region
  * Công cụ: AWS CLI, SAM / CDK / Terraform (nếu có)
  * Quyền IAM cần thiết
* **Hướng dẫn chi tiết**:

  * Chia rõ từng bước (Step 1, Step 2, …)
  * Có screenshot / CLI / console guide
  * Thực hiện được end-to-end
* **Test & validation**:

  * Gửi request
  * Xem log
  * Check metric
  * Kiểm thử lỗi
  * Kết quả mong đợi
* **Clean-up**:

  * Xóa resource
  * Delete stack
  * Xóa bucket
  * Xóa alarm

#### 4.4. Tài liệu workshop & trình bày (0.5 điểm)

* **Song ngữ**:

  * Nội dung chính có cả tiếng Việt và tiếng Anh
  * Dịch đúng ý, không lệch nghĩa nghiêm trọng
* **Cấu trúc website**:

  * Đúng layout template
  * Mục lục rõ ràng
  * Navigation hợp lý
* **Trình bày**:

  * Text dễ đọc
  * Có code block
  * Có hình ảnh minh họa
  * Ít lỗi chính tả

#### 4.5. Đóng góp cá nhân (0.5 điểm)

* **Mức độ tự làm**:

  * Không chỉ copy mẫu
  * Có tùy biến:

    * Thêm feature
    * Thêm service
    * Data khác
    * Cách test khác
* **Reflection ngắn**:

  * Nêu khó khăn gặp phải
  * Cách giải quyết
  * Hướng phát triển trong tương lai
