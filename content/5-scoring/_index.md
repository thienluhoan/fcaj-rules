---
title: "Tiêu chí chấm Workshop"
date: 2025-01-12
weight: 5
chapter: false
pre: " <b> 5. </b> "
---

Tài liệu này mô tả **barem tổng quan**, **checklist chấm điểm chi tiết** và **bảng tiêu chí trừ điểm / mất điểm** áp dụng cho sinh viên thực tập tham gia chương trình First Cloud AI Journey (FCAJ). Đây là căn cứ chính thức để đánh giá toàn diện kết quả thực tập của sinh viên.

---

### 1. Barem tổng quan

| Nhóm tiêu chí       | Điểm tối đa | Ghi chú                   |
| ------------------- | ----------- | ------------------------- |
| Worklog / Blog      | **1.0**     |                           |
| Proposal / Workshop | **5.0**     | Architecture chiếm 4.0    |
| Thái độ / tác phong | **2.0**     |                           |
| Chuyên cần          | **1.5**     |                           |
| Bonus               | **0.5**     | Chỉ cộng khi đủ điều kiện |
| **TỔNG**            | **10.0**    |                           |

{{% notice info %}}
Yêu cầu điểm tổng kết **tối thiểu 7.0/10** để được xét chứng nhận hoàn thành thực tập.
{{% /notice %}}

---

### 2. Checklist chấm điểm

#### 2.1. Worklog – 1.0 điểm

##### Blog & Daily Worklog (0.5 điểm)

<table>
  <tr>
    <th>Checklist</th>
    <th>Cách chấm</th>
    <th>Tối đa</th>
  </tr>
  <tr>
    <td>[ ] Có Blog và có Daily Worklog</td>
    <td>Thiếu 1 bài Blog: <strong>-0.2đ</strong></td>
    <td rowspan="3" style="vertical-align: middle; text-align: left;"><strong>0.5</strong></td>
  </tr>
  <tr>
    <td>[ ] Có ít nhất 3 bài Blog</td>
    <td>Blog tự viết vẫn được tính</td>
  </tr>
  <tr>
    <td>[ ] Daily Worklog có ghi nhận công việc/học tập</td>
    <td></td>
  </tr>
</table>

##### Template & Nội dung (0.5 điểm)

<table>
  <tr>
    <th>Checklist</th>
    <th>Cách chấm</th>
    <th>Tối đa</th>
  </tr>
  <tr>
    <td>[ ] Template/format đúng</td>
    <td>Template + format: <strong>0.2đ</strong></td>
    <td rowspan="3" style="vertical-align: middle; text-align: left;"><strong>0.5</strong></td>
  </tr>
  <tr>
    <td>[ ] Nội dung rõ ràng, thể hiện đã học/làm gì</td>
    <td>Nội dung rõ ràng + reference: <strong>0.3đ</strong></td>
  </tr>
  <tr>
    <td>[ ] Có reference khi cần</td>
    <td></td>
  </tr>
</table>

{{% notice warning %}}
Nếu **Blog** HOẶC **Daily Worklog** không có 1 trong 2 thì mục này = **0 điểm**.
{{% /notice %}}

---

#### 2.2. Workshop – 5.0 điểm

{{% notice warning %}}
**QUY TẮC KHÓA WORKSHOP:** Không có Architecture **HOẶC** không trình bày Workshop/Proposal thì điểm Workshop = **0** (1 trong 2 không có).
{{% /notice %}}

##### Architecture / Production (3.5 điểm)

**Tiêu chuẩn AWS (0.5 điểm)**

<table>
  <tr>
    <th>Checklist</th>
    <th>Cách chấm</th>
    <th>Tối đa</th>
  </tr>
  <tr>
    <td>[ ] Đúng AWS service/icon/name</td>
    <td>Chấm lỗi icon, tên service, luồng và cách dùng service</td>
    <td rowspan="4" style="vertical-align: middle; text-align: left;"><strong>0.5</strong></td>
  </tr>
  <tr>
    <td>[ ] Service dùng đúng mục đích</td>
    <td></td>
  </tr>
  <tr>
    <td>[ ] Luồng/kết nối hợp lý</td>
    <td></td>
  </tr>
  <tr>
    <td>[ ] Boundary/khung thể hiện đúng</td>
    <td></td>
  </tr>
</table>

**Thẩm mỹ diagram (0.2 điểm)**

<table>
  <tr>
    <th>Checklist</th>
    <th>Tối đa</th>
  </tr>
  <tr>
    <td>[ ] Ảnh rõ nét</td>
    <td rowspan="4" style="vertical-align: middle; text-align: left;"><strong>0.2</strong></td>
  </tr>
  <tr>
    <td>[ ] Không chồng chéo</td>
  </tr>
  <tr>
    <td>[ ] Bố cục cân đối</td>
  </tr>
  <tr>
    <td>[ ] Luồng dễ theo dõi</td>
  </tr>
</table>

**AWS Well-Architected Framework (3.0 điểm)**

| Pillar                     | Cách chấm                                                            | Tối đa                  |
| -------------------------- | -------------------------------------------------------------------- | ----------------------- |
| [ ] Operational Excellence | Đánh giá theo AWS Well-Architected, phù hợp scope project            | **0.5**                 |
| [ ] Security               | Đánh giá theo AWS Well-Architected, **chấm gắt** các vấn đề security | **0.5**                 |
| [ ] Reliability            | Đánh giá failure handling, availability, recovery phù hợp project    | **0.5**                 |
| [ ] Performance Efficiency | Đánh giá lựa chọn service/tài nguyên và khả năng scale               | **0.5**                 |
| [ ] Cost Optimization      | Đánh giá cost-awareness và tối ưu chi phí                            | **0.5**                 |
| [ ] Sustainability         | Đánh giá sử dụng tài nguyên hợp lý, tránh over-provisioning          | **0** *(không áp dụng)* |

**Điểm tự vẽ / tự thiết kế (0.3 điểm)**

<table>
  <tr>
    <th>Checklist</th>
    <th>Tối đa</th>
  </tr>
  <tr>
    <td>[ ] Tự vẽ / tự arrange Architecture</td>
    <td rowspan="2" style="vertical-align: middle; text-align: left;"><strong>0.3</strong></td>
  </tr>
  <tr>
    <td>[ ] Giải thích được diagram của mình</td>
  </tr>
</table>

{{% notice warning %}}
**Quy tắc về GenAI trong Architecture:**
- Architecture **hoàn toàn do AI tạo** = **0 điểm**.
- Có dùng AI và đã chỉnh nhưng **vẫn còn lỗi rõ ràng** (sai icon, sai tên service, chồng chéo…): **trừ 1đ** (0.5 Tiêu chuẩn AWS + 0.3 Tự vẽ + 0.2 Thẩm mỹ).
- Vẽ **không đúng tiêu chuẩn AWS** nhưng tự tay vẽ = **0.5đ** (công vẽ).
{{% /notice %}}

> Ở mục Workshop, sinh viên **phải thể hiện được** như Architecture đã vẽ.

##### Demo (0.5 điểm)

| Checklist                                                       | Tối đa  |
| --------------------------------------------------------------- | ------- |
| [ ] Có demo sản phẩm bằng live demo, video hoặc link production | **0.5** |

##### Trình bày (1.0 điểm)

<table>
  <tr>
    <th>Checklist</th>
    <th>Cách chấm</th>
    <th>Tối đa</th>
  </tr>
  <tr>
    <td>[ ] Trình bày đầy đủ Proposal</td>
    <td>Chấm 0–1 tùy độ chi tiết</td>
    <td rowspan="3" style="vertical-align: middle; text-align: left;"><strong>1.0</strong></td>
  </tr>
  <tr>
    <td>[ ] Trình bày đầy đủ Workshop</td>
    <td></td>
  </tr>
  <tr>
    <td>[ ] Có phần COST</td>
    <td><strong>Thiếu COST = 0 điểm</strong> mục này</td>
  </tr>
</table>

---

#### 2.3. Thái độ / tác phong – 2.0 điểm

##### Thái độ (1.0 điểm)

<table>
  <tr>
    <th>Checklist</th>
    <th>Tối đa</th>
  </tr>
  <tr>
    <td>[ ] Tinh thần học hỏi</td>
    <td rowspan="4" style="vertical-align: middle; text-align: left;"><strong>1.0</strong></td>
  </tr>
  <tr>
    <td>[ ] Chủ động</td>
  </tr>
  <tr>
    <td>[ ] Lịch sự, lễ phép</td>
  </tr>
  <tr>
    <td>[ ] Trung thực</td>
  </tr>
</table>

{{% notice warning %}}
- Tốt đầy đủ: **1.0 điểm**.
- **Gian dối / không trung thực = 0 điểm** mục Thái độ.
{{% /notice %}}

##### Tuân thủ nội quy (1.0 điểm)

<table>
  <tr>
    <th>Checklist</th>
    <th>Tối đa</th>
  </tr>
  <tr>
    <td>[ ] Không vắng trái quy định</td>
    <td rowspan="3" style="vertical-align: middle; text-align: left;"><strong>1.0</strong></td>
  </tr>
  <tr>
    <td>[ ] Không tự ý bỏ về</td>
  </tr>
  <tr>
    <td>[ ] Không làm việc riêng / đi trễ / vi phạm trang phục – nội quy</td>
  </tr>
</table>

{{% notice warning %}}
- Bắt đầu từ **1.0** và áp dụng **bảng trừ điểm**.
- Vi phạm nghiêm trọng có thể bị **trừ thêm sang phần Thái độ**.
- **Hút thuốc** tại văn phòng: **0 điểm** cả Thái độ và Tuân thủ nội quy.
{{% /notice %}}

> Chi tiết từng vi phạm và mức trừ: [4. Xử lý vi phạm](../4-violations/).

---

#### 2.4. Chuyên cần – 1.5 điểm

##### Office (0.5 điểm)

| Checklist             | Cách chấm                                                                | Tối đa  |
| --------------------- | ------------------------------------------------------------------------ | ------- |
| [ ] Đủ 10 buổi office | Hoặc theo quy định booking: từ 20 bookings trở lên và có ít nhất 6 slots | **0.5** |

> Thiếu 1 buổi: **-0.1đ/buổi** đến hết 0.5 điểm.

##### Event (1.0 điểm)

<table>
  <tr>
    <th>Checklist</th>
    <th>Cách chấm</th>
    <th>Tối đa</th>
  </tr>
  <tr>
    <td>[ ] Event 1 – có ảnh hợp lệ</td>
    <td></td>
    <td rowspan="3" style="vertical-align: middle; text-align: left;"><strong>1.0</strong></td>
  </tr>
  <tr>
    <td>[ ] Event 2 – có ảnh hợp lệ</td>
    <td>Đủ 3 event có ảnh legit: <strong>1.0 điểm</strong></td>
  </tr>
  <tr>
    <td>[ ] Event 3 – có ảnh hợp lệ</td>
    <td></td>
  </tr>
</table>

{{% notice info %}}
- Thiếu 1 event: **-0.3đ**.
- Event thiếu ảnh / ảnh không rõ: event đó chỉ **+0.2đ**.
{{% /notice %}}

---

#### 2.5. Bonus – 0.5 điểm

| Điều kiện bắt buộc           | Yêu cầu                            |
| ---------------------------- | ---------------------------------- |
| Nhóm 3 – Thái độ / tác phong | Đạt full **2.0/2.0**               |
| Nhóm 4 – Chuyên cần          | Đạt full **1.5/1.5**               |
| Hoàn thành Workshop/project  | Có Architecture + Demo + Trình bày |

{{% notice tip %}}
**ĐỦ CẢ 3 ĐIỀU KIỆN** → Bonus **+0.5 điểm**.
{{% /notice %}}

---

### 3. Bảng tiêu chí trừ điểm / mất điểm

Bảng dưới đây tổng hợp **toàn bộ các trường hợp bị trừ hoặc mất điểm**, áp dụng thống nhất cho tất cả các nhóm tiêu chí.

#### 3.1. Worklog

| Trường hợp                                       | Mức trừ / giới hạn             | Ghi chú                                      |
| ------------------------------------------------ | ------------------------------ | -------------------------------------------- |
| Thiếu 1 bài Blog                                 | **-0.1đ / bài**                |                                              |
| Không có Blog HOẶC không có Daily Worklog        | **Mục Blog/Daily Worklog = 0** | Một trong hai không đạt thì mất điểm mục này |
| Template/format không đạt                        | Mất tối đa **0.2đ**            | Không cộng phần Template/format              |
| Nội dung không rõ đã học/làm gì, thiếu reference | Mất tối đa **0.3đ**            |                                              |

#### 3.2. Architecture

| Trường hợp                                                    | Mức trừ / giới hạn                | Ghi chú                                          |
| ------------------------------------------------------------- | --------------------------------- | ------------------------------------------------ |
| Architecture hoàn toàn do GenAI tạo                           | **Architecture = 0**              | Không chấm                                       |
| Có dùng AI, đã chỉnh nhưng còn lỗi rõ                         | **-1đ**                           | Mất 0.5 Tiêu chuẩn AWS + 0.3 Tự vẽ + 0.2 Thẩm mỹ |
| Sai AWS service/icon/name/flow hoặc dùng service sai mục đích | Trừ trong **0.5đ** Tiêu chuẩn AWS | Mức trừ theo mức độ sai                          |
| Diagram mờ, chồng chéo, bố cục/flow khó đọc                   | Trừ trong **0.2đ** Thẩm mỹ        | Mức trừ theo mức độ                              |
| Không đáp ứng 1 pillar Well-Architected                       | **Trừ 0–0.5 / pillar**            | 6 pillars, tổng tối đa 3.0                       |

#### 3.3. Production / Workshop

| Trường hợp                                                   | Mức trừ / giới hạn             | Ghi chú                                      |
| ------------------------------------------------------------ | ------------------------------ | -------------------------------------------- |
| Không thể hiện được như Architecture đã vẽ                   | **Trừ ½ số điểm** Architecture |                                              |
| Không vẽ Architecture HOẶC không trình bày Workshop/Proposal | **Workshop = 0**               | Quy tắc khóa Workshop                        |
| Không demo và không có sản phẩm                              | **Demo = 0**                   |                                              |
| Thiếu phần COST                                              | **Trình bày = 0**              | Điều kiện bắt buộc của mục Trình bày         |
| Trình bày quá ngắn / thiếu chi tiết                          | Chấm trong khoảng **0–1đ**     | Tùy mức độ đầy đủ COST, Proposal và Workshop |

#### 3.4. Thái độ / tác phong

| Trường hợp                                         | Mức trừ / giới hạn        | Ghi chú                                                     |
| -------------------------------------------------- | ------------------------- | ----------------------------------------------------------- |
| Gian dối / không trung thực                        | **Thái độ = 0đ**          | Ví dụ: cố tình khai/đọc sai thông tin, chối hành vi rõ ràng |
| Vắng                                               | **-0.3đ / buổi**          | Trừ trong mục Tuân thủ nội quy 1.0                          |
| Tự ý bỏ về                                         | **Tuân thủ nội quy = 0đ** | Áp dụng ngay cho mục này                                    |
| Vi phạm nội quy: làm việc riêng, đi trễ, mang dép… | **-0.2đ / lần**           | Tùy mức độ có thể trừ thêm sang Thái độ                     |
| Hút thuốc tại văn phòng                            | **0 điểm cả 2 mục**       | Thái độ = 0/1 và Tuân thủ = 0/1                             |

#### 3.5. Chuyên cần

| Trường hợp                                      | Mức trừ / giới hạn     | Ghi chú                   |
| ----------------------------------------------- | ---------------------- | ------------------------- |
| Thiếu buổi office                               | **-0.1đ / buổi**       | Trừ đến hết 0.5 điểm      |
| Thiếu event                                     | **-0.3đ / event**      | So với yêu cầu đủ 3 event |
| Có tham gia nhưng thiếu ảnh / ảnh không rõ ràng | Event đó chỉ **+0.2đ** | Ảnh phải đủ rõ và hợp lệ  |

#### 3.6. Bonus

| Trường hợp                                                          | Mức trừ / giới hạn | Ghi chú                                        |
| ------------------------------------------------------------------- | ------------------ | ---------------------------------------------- |
| Không full Nhóm 3 hoặc Nhóm 4 hoặc chưa hoàn thành Workshop/project | **Bonus = 0**      | Bonus chỉ cộng khi đủ đồng thời cả 3 điều kiện |

---

### 4. Bảng tổng kết

| Nhóm        | Worklog | Workshop | Thái độ | Chuyên cần | Bonus | TỔNG |
| ----------- | ------- | -------- | ------- | ---------- | ----- | ---- |
| Điểm tối đa | 1.0     | 5.0      | 2.0     | 1.5        | 0.5   | 10   |

---

**Liên quan:** [3. Quy định về project](../3-project/) · [4. Xử lý vi phạm](../4-violations/) · [1.1. Chuyên cần](../1-regulations/1.1-diligence/)
