<div align="center">

# 🏥 HỆ THỐNG QUẢN TRỊ QUY TRÌNH NGHIỆP VỤ

### Đề tài: Hệ thống quản trị quy trình nghiệp vụ tại Hệ thống nhà thuốc FPT Long Châu

**Báo cáo Đồ án cuối kỳ — Môn Hệ thống Quản trị Quy trình Nghiệp vụ**

Trường Đại học Công nghệ Thông tin — Trung tâm Phát triển Công nghệ Thông tin

![Status](https://img.shields.io/badge/Đồ_án-Rubik_1-2E86C1)
![BPMN](https://img.shields.io/badge/Chuẩn-BPMN_2.0-27AE60)
![Domain](https://img.shields.io/badge/Lĩnh_vực-Dược_phẩm_bán_lẻ-E67E22)
![Docs](https://img.shields.io/badge/Định_dạng-Word_docx-8E44AD)

</div>

---

## 📌 Giới thiệu

Đồ án phân tích và mô hình hóa các **quy trình nghiệp vụ (Business Process Management – BPM)** tại hệ thống nhà thuốc **FPT Long Châu** — một trong những chuỗi bán lẻ dược phẩm dẫn đầu Việt Nam.

Với quy mô lớn và hoạt động phức tạp, Long Châu đối mặt nhiều thách thức: chi phí vận hành cao, một số quy trình còn thủ công và chưa chuẩn hóa. Mục tiêu của đồ án là **liệt kê, phân loại, mô hình hóa và phân tích** các quy trình then chốt, từ đó đề xuất hướng cải tiến và số hóa.

**Giảng viên hướng dẫn:** ThS. Hà Lê Hoài Trung

---

## 👥 Thành viên nhóm

**Giảng viên hướng dẫn:** ThS. Hà Lê Hoài Trung

| STT | Họ tên               |   MSSV   |
| :-: | :------------------- | :------: |
|  1  | Nguyễn Quốc Tài      | 25410295 |
|  2  | Trần Thiện Thiên Tân | 25410302 |
|  3  | Bùi Thị Kim Tuyến    | 25410329 |
|  4  | Trần Đức Nhân        | 25410267 |
|  5  | Phạm Thị Hằng Ni     | 25410272 |
|  6  | Lê Thanh Tuấn        | 25410328 |

---

## 🗂️ Kiến trúc quy trình

Hệ thống được phân loại thành **3 nhóm quy trình**:

### 1. Quy trình Quản lý (Management Process)

| STT | Quy trình                                 | Người làm |
| :-: | :---------------------------------------- | :-------- |
|  1  | Quản lý mua hàng và cung ứng              | Tài       |
|  2  | **Quản lý kho vận (Logistics & GSP)**     | Tuấn      |
|  3  | Quản lý bán hàng và tư vấn tại quầy (GPP) | Tuấn      |
|  4  | Quản lý chất lượng và xử lý rủi ro        | Tài       |
|  5  | Quản lý nhân sự và đào tạo dược sĩ        | Tuấn      |

### 2. Quy trình Cốt lõi (Core Process)

| STT | Quy trình                                             | Người làm  |
| :-: | :---------------------------------------------------- | :--------- |
|  1  | Xử lý đơn thuốc và bán hàng tại quầy (Core Front-End) | Ni + Tuyến |
|  2  | Dự trù và châm hàng tự động (Auto-Replenishment)      | Ni + Tuyến |
|  3  | Kiểm soát chất lượng và bảo quản (GSP/GDP)            | Ni + Tuyến |
|  4  | Vận hành đơn hàng online và giao hàng nhanh (O2O)     | Tuyến      |
|  5  | Quản lý ca trực và giao ban hằng ngày tại cửa hàng    | Tuyến      |

### 3. Quy trình Phối hợp / Hỗ trợ (Support Process)

| STT | Quy trình                                            | Người làm |
| :-: | :--------------------------------------------------- | :-------- |
|  1  | Kiểm soát nội bộ và pháp lý (Compliance & Legal)     | —         |
|  2  | Hỗ trợ công nghệ thông tin (IT Support & Helpdesk)   | Tân       |
|  3  | Quản trị tài chính và kế toán (Finance & Accounting) | Tân       |
|  4  | Quản trị cơ sở vật chất và bảo trì (Maintenance)     | Nhân      |
|  5  | Chăm sóc khách hàng và hậu mãi (Customer Service)    | Nhân      |

---

## 📚 Nội dung báo cáo

|     Chương     | Nội dung                                                              |
| :------------: | :-------------------------------------------------------------------- |
|  **Chương I**  | Giới thiệu & tóm tắt nội dung                                         |
| **Chương II**  | Liệt kê và phân loại quy trình nghiệp vụ (12+ quy trình theo 3 nhóm)  |
| **Chương III** | Mô hình hóa quy trình nghiệp vụ theo chuẩn **BPMN 2.0**               |
| **Chương IV**  | Phân tích quy trình (VA/BVA/NVA, chi phí Lean, chỉ số PCE) & Kết luận |

---

## 📁 Cấu trúc thư mục

```
F34-LT-CNTT-HTQTQTNV/
├── README.md                          # Tài liệu này
├── DoAn_HTQTNV_Mau.docx               # File mẫu báo cáo tổng hợp
├── BẢNG PHÂN CÔNG_rubik1.xlsx         # Bảng phân công công việc
├── Rubik Đánh giá Bài tập Đồ Án.xlsx  # Tiêu chí đánh giá (rubric)
│
├── 25410295_Tai/    → Nhóm Quản lý (mua hàng, kho vận, GPP, chất lượng, nhân sự)
├── 25410328_Tuan/   → Nhóm Quản lý (kho vận, GPP, nhân sự) — làm chung với Tài
├── 25410272_Ni/     → Nhóm Cốt lõi (Core Front-End, Auto-Replenishment, GSP/GDP)
├── 25410302_Tan/    → Nhóm Hỗ trợ (IT Support, Finance & Accounting)
└── 25410267_Nhan/   → Nhóm Hỗ trợ (Maintenance, Customer Service / CRM)
```

---

## 🛠️ Công cụ & Phương pháp

- **Chuẩn mô hình hóa:** BPMN 2.0 (Pool, Lane, Gateway, biểu mẫu đi kèm)
- **Phương pháp thu thập dữ liệu:** phỏng vấn, phân tích biểu mẫu, khảo sát thực tế
- **Phân tích quy trình:** giá trị gia tăng (VA / BVA / NVA), nhận diện lãng phí Lean (Move, Hold, Over-do), chỉ số hiệu suất (PCE)
- **Định hướng cải tiến:** tự động hóa & số hóa quy trình, tích hợp ERP

---

<div align="center">

_Tp. Hồ Chí Minh, tháng 08 năm 2026_

</div>
