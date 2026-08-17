# Lingora — Nền tảng Học Ngoại ngữ Cá nhân hóa Tích hợp AI

> **Dự án Đồ án Chuyên ngành / Bài tập Lớn (BTL)**  
> **Tác giả:** Phạm Nguyễn Thanh Tùng  
> **Repository:** [https://github.com/PhamNguyenThanhTung/BTL](https://github.com/PhamNguyenThanhTung/BTL)

---

## 1. Giới thiệu Dự án (Project Overview)

**Lingora** là hệ thống học ngoại ngữ hiện đại được thiết kế theo quy trình kỹ nghệ phần mềm chuẩn mực, tích hợp công nghệ trí tuệ nhân tạo (AI) nhằm giải quyết bài toán tiếp thu và duy trì tri thức ngôn ngữ lâu dài của người học.

Dự án được đánh giá qua 3 góc nhìn học thuật liên ngành:
1. **Kỹ nghệ Phần mềm (Software Engineering - Project 1):** Kiến trúc ứng dụng Web học viên (`Next.js 15`), bảng điều khiển quản trị (`Admin Dashboard`), backend cơ sở dữ liệu phân quyền (`Supabase PostgreSQL + RLS + RPC`), lưu trữ đa phương tiện bảo mật (`Storage`), và quy trình kiểm thử toàn diện.
2. **Học máy (Machine Learning - ML):** Thuật toán mô hình hóa trí nhớ (Spaced Repetition System - SRS) với mô hình Deep Knowledge Tracing (DKT-LSTM) kết hợp Half-Life Regression (HLR) và bộ điều phối Rule-based Scheduler.
3. **Xử lý Ngôn ngữ Tự nhiên (Natural Language Processing - NLP):** Trợ lý hội thoại tình huống (Contextual Roleplay Chatbot) dựa trên kiến trúc Transformer Seq2Seq (T5-small) hỗ trợ giao tiếp hai chiều và phản hồi ngôn ngữ.

---

## 2. Quy trình & Lộ trình Phát triển Chuẩn mực (Engineering Process & Roadmap)

Dự án được triển khai tuần tự theo đúng quy trình công nghệ phần mềm thực tế:

```text
Giai đoạn 1: Kỹ nghệ Yêu cầu & Khảo sát Người dùng (Requirements Engineering & User Research)
    │  ├─ Kế hoạch khảo sát & Bảng câu hỏi người dùng (Survey Instruments)
    │  ├─ Kịch bản phỏng vấn sâu (In-depth Interviews)
    │  ├─ Khảo sát & Phân tích đối thủ / Sản phẩm tương tự (Competitor Benchmark)
    │  ├─ Tổng hợp Nỗi đau & Nhu cầu người dùng (Pain Points & User Needs)
    │  └─ Danh mục Yêu cầu Chức năng (FR) & Phi chức năng (NFR)
    ▼
Giai đoạn 2: Phân tích & Mô hình hóa Hệ thống (System Analysis & Modeling)
    │  ├─ Danh mục Tác nhân & Quyền hạn (Stakeholders & Actors)
    │  ├─ Danh mục & Đặc tả chi tiết Use Case (Use Case Specifications)
    │  ├─ Sơ đồ Tuần tự & Luồng nghiệp vụ (Business & Sequence Flows)
    │  ├─ Sơ đồ Thực thể Quan hệ (ERD) & Từ điển Dữ liệu (Data Dictionary)
    │  └─ Ranh giới Hệ thống & Ràng buộc Kỹ thuật (System Boundaries & Constraints)
    ▼
Giai đoạn 3: Thiết kế Kiến trúc Hệ thống (Architecture & Design Baseline)
    │  ├─ Thiết kế Kiến trúc Thành phần (Component Architecture)
    │  ├─ Hợp đồng Giao tiếp API (API Contract & Error Envelope)
    │  ├─ Chiến lược Cơ sở dữ liệu & RLS Security Matrix
    │  └─ Ma trận Truy vết Yêu cầu (Traceability Matrix)
    ▼
Giai đoạn 4: Triển khai & Kiểm thử Từng bước (Implementation & Testing Milestones)
    │  ├─ M1: Khởi tạo Nền tảng (Platform & Authentication Foundation)
    │  ├─ M2: Luồng Học tập Cốt lõi (Core Lesson Flow & Exercise Engine)
    │  ├─ M3: Bảng Quản trị Nội dung (Admin Content Management)
    │  ├─ M4: Tích hợp Mô hình AI/ML & Huấn luyện (AI Model Integration)
    │  └─ M5: Đóng băng Tính năng & Triển khai Production (Deployment & Reports)
```

---

## 3. Cấu trúc Thư mục Dự án

```text
lingora/
├── docs/                        # Tài liệu kỹ thuật, yêu cầu, phân tích & báo cáo
│   ├── requirements/            # Tài liệu khảo sát, phỏng vấn và đặc tả yêu cầu
│   ├── analysis/                # Đặc tả Use Case, luồng nghiệp vụ và phân tích hệ thống
│   ├── data-model/              # Sơ đồ ERD và từ điển dữ liệu
│   └── architecture/            # Đặc tả kiến trúc, API contract và bảo mật
├── README.md                    # Giới thiệu tổng quan dự án
└── .gitignore                   # Cấu hình bỏ qua tệp nhạy cảm và build artifacts
```

---

## 4. Trạng thái Hiện tại (Current Status)

Dự án hiện đang ở **Giai đoạn 1: Kỹ nghệ Yêu cầu & Khảo sát Người dùng (Requirements Engineering & User Research)**. Toàn bộ các tài liệu khảo sát, phỏng vấn, benchmark và phân tích nhu cầu đang được tổng hợp trước khi hoàn thiện baseline yêu cầu.
