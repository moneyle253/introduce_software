# XÂY DỰNG ỨNG DỤNG BÁN LẺ TẠP HÓA 4.0 — README

Họ tên: Lê Hoàng Tiền 

MSSV: K23DTCN309 

Lớp: HKV_NMCNPM Github Profile: https://github.com/moneyle253
Nhập môn Công nghệ Phần mềm — Lab Practices

---

## Mục lục

1. [Tổng quan dự án](#tổng-quan-dự-án)
2. [Các Lab & Kết quả yêu cầu](#các-lab--kết-quả-yêu-cầu)
3. [Project Definition (mẫu)](#project-definition-mẫu)
4. [Software Requirements Specification — SRS (mẫu)](#software-requirements-specification--srs-mẫu)
5. [Thiết kế & UML (mẫu nội dung)](#thiết-kế--uml-mẫu-nội-dung)
6. [Quản lý dự án & GitHub](#quản-lý-dự-án--github)
7. [Cấu trúc repo đề xuất](#cấu-trúc-repo-đề-xuất)
8. [Hướng dẫn nộp bài & checklist](#hướng-dẫn-nộp-bài--checklist)

---

## Tổng quan dự án

**Tên dự án:** Hệ thống Bán lẻ Tạp hóa 4.0 (Grocery Shop 4.0)
**Mục tiêu:** Xây dựng web app cho cửa hàng tạp hóa, hỗ trợ quản lý hàng hóa, tồn kho, bán hàng, khách hàng & báo cáo.
**Công nghệ gợi ý:** Frontend (React/Vue) + Backend (Node.js/Express | Django | SpringBoot | ASP.NET Core) + DB (MySQL / SQL Server).

---

## Các Lab & Kết quả yêu cầu

### Lab 1 — Khởi tạo dự án & Định nghĩa yêu cầu

* Viết **Project Definition**.
* Viết **SRS** theo template (tập tin: `docs/SRS.docx` hoặc `.md`).
* Nộp: file `.doc` chứa Project Definition + SRS.

### Lab 2 — Phân tích & Mô hình hóa

* Use Case Diagram + mô tả use case.
* Activity Diagram cho 1 chức năng chính.
* Class Diagram & Sequence Diagram.
* ERD & DFD (Level 0, Level 1).
* Nộp: ảnh/diagram trong `docs/uml/`.

### Lab 3 — Quản lý dự án & Cấu hình

* WBS + Gantt Chart (Jira/Confluence hoặc Gantt ở Excel).
* GitHub repo, commit tài liệu.
* Risk Management document.
* Nộp: `docs/project-plan.pdf` + link repo.

### Lab 4 — Thiết kế, Kiểm thử & Triển khai

* Thiết kế UI mẫu, database schema.
* Cài đặt 1 module theo MVC.
* Unit tests & quản lý lỗi (GitHub Issues / Mentis).
* Triển khai demo (Heroku/Azure/XAMPP).
* Nộp: source code + report.

---

## Project Definition (mẫu)

**1. Tên dự án**
**2. Mô tả ngắn gọn (1 đoạn)**
**3. Bối cảnh & Lý do thực hiện**
**4. Mục tiêu & Phạm vi**

* Mục tiêu chính
* Phạm vi: (ví dụ: Quản lý kho, POS, Khách hàng, Báo cáo)
  **5. Người liên quan (Stakeholders)**
* Chủ cửa hàng, Nhân viên bán hàng, Quản lý kho, Khách hàng, Giảng viên.
  **6. Ràng buộc & Giả định**
* Ngôn ngữ, CSDL, Thời gian, Ngân sách (nếu có).
  **7. Kết quả bàn giao**
* Tài liệu, Source code, Database script, Demo.

---

## SRS (mẫu cấu trúc & nội dung chính)

> *Lưu ý: copy phần này vào file ****************`docs/SRS.docx`**************** hoặc ****************`docs/SRS.md`**************** và điền chi tiết.*

1. **Giới thiệu**

   * Mục đích tài liệu
   * Phạm vi hệ thống
   * Định nghĩa, thuật ngữ
2. **Tổng quan tổng thể**

   * Môi trường hoạt động
   * Người dùng & yêu cầu chung
3. **Yêu cầu chức năng (Functional Requirements)**

   * FR1: Quản lý sản phẩm (CRUD)
   * FR2: Quản lý kho (nhập/xuất, tồn)
   * FR3: POS: tạo hóa đơn, thanh toán
   * FR4: Quản lý khách hàng (thẻ, lịch sử mua)
   * FR5: Báo cáo (bán hàng, tồn kho)
   * Mỗi FR nên có: ID, mô tả, tiền đề, bước chính, dữ liệu trả về
4. **Yêu cầu phi chức năng (Non-functional Requirements)**

   * Hiệu năng: X user đồng thời
   * Bảo mật: authentication, authorization
   * Khả năng mở rộng, backup, logging
   * Tương thích trình duyệt
5. **Ràng buộc hệ thống**

   * CSDL: MySQL 8
   * Platform: Linux/Windows server
6. **Use cases (tóm tắt)**
7. **Priority và roadmap phát triển**
8. **Appendix**: DB schema sơ bộ, API endpoints mẫu

---

## Thiết kế & UML (mẫu nội dung cần nộp)

* Use Case Diagram (PNG/SVG) + mô tả từng use case (actor, precondition, flow, postcondition).
* Activity Diagram cho tính năng: **Tạo hóa đơn & thanh toán**.
* Class Diagram: các lớp domain (Product, Order, Customer, Inventory, User).
* Sequence Diagram: Tạo đơn hàng (frontend → backend → db → thanh toán).
* ERD: tables chính & quan hệ.
* DFD: Level 0 (hệ thống chính), Level 1 (quy trình bán hàng, quản lý kho).

---

## Quản lý dự án & GitHub

**Project Plan:**

* Tạo WBS (Work Breakdown Structure)
* Gantt chart: thời gian, milestone (Lab1..Lab4, Mid-demo, Final)
* Risk log: mô tả, xác suất, ảnh hưởng, biện pháp giảm thiểu

**GitHub best practices:**

* Repo: `grocery-shop-4.0`
* Branching: `main` (production), `dev` (tích hợp), feature branches `feature/<tên>`
* Commit message: (Conventional Commits) `feat: add product api` / `fix: correct stock calc`.
* PR template & Issue templates (bug, feature request)

**Ví dụ liên kết (đưa vào README)**

* SRS: `./docs/SRS.md`
* UML: `./docs/uml/`
* Project Plan: `./docs/project-plan.pdf`
* Repo code: `https://github.com/<org-or-user>/grocery-shop-4.0`

---

## Cấu trúc repo (đề xuất)

```
/grocery-shop-4.0
│
├─ /docs
│   ├─ SRS.md
│   ├─ ProjectDefinition.docx
│   ├─ project-plan.pdf
│   └─ /uml
│       ├─ usecase.png
│       ├─ class.png
│       └─ erd.png
│
├─ /src
│   ├─ /backend
│   └─ /frontend
│
├─ /db
│   └─ schema.sql
│
├─ /tests
│
├─ README.md  <-- (bản rút gọn của file này)
└─ .github
    ├─ ISSUE_TEMPLATE.md
    └─ PULL_REQUEST_TEMPLATE.md
```

---

## Hướng dẫn nộp bài & Checklist (cần có trong README)

*

---

## Một số mẫu nhúng vào README (Markdown)

````
[Project SRS](./docs/SRS.md)
[UML diagrams](./docs/uml/)
[Project Plan (PDF)](./docs/project-plan.pdf)

## Clone & chạy (ví dụ Node.js)
```bash
git clone https://github.com/<user>/grocery-shop-4.0.git
cd grocery-shop-4.0/src/backend
npm install
npm run dev
````

## Liên hệ

* Student profile: https://github.com/moneyle253

```

---

### Ghi chú
- Thực hiện: sao chép các mẫu vào file `.docx` hoặc `.md`, hoàn thiện thông tin nhóm và mô tả chi tiết ở mỗi phần.  
- Muốn tôi chuyển sẵn `SRS.docx` hoặc `README.md` thành file thực tế trong repo không? (tôi có thể tạo bản README.md chi tiết hoặc file SRS theo template để bạn tải về).

---

*Tài liệu này là bản mẫu README để đưa vào repo. Chỉnh sửa tên nhóm, link GitHub và các chi tiết thực tế trước khi nộp.*

```
