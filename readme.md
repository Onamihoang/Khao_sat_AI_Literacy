# Khảo sát AI Literacy cho Nhân viên Ngân hàng

Dự án nghiên cứu và xây dựng framework đánh giá năng lực AI (AI Literacy) cho nhân viên ngân hàng Việt Nam.

## Mục tiêu

- Xây dựng bộ công cụ đánh giá AI literacy phù hợp với đặc thù ngân hàng Việt Nam
- Thiết kế survey dựa trên framework quốc tế (UNESCO, EU DigComp) và thang đo học thuật đã validated (MAILS, AILS)
- Tham khảo best practices từ các ngân hàng hàng đầu (JPMorgan, DBS, HSBC, Standard Chartered)

## Cấu trúc thư mục

```
.
├── README.md                                    # File này
├── deep_research/
│   └── ai_literacy_framework_research.md        # Nghiên cứu tổng hợp chi tiết
└── surveys/
    ├── nhan_vien/                               # Khảo sát cho nhân viên
    │   ├── khao_sat_nhan_vien_co_ban.md         # Cấp độ cơ bản
    │   ├── khao_sat_nhan_vien_trung_binh.md     # Cấp độ trung bình
    │   └── khao_sat_nhan_vien_nang_cao.md       # Cấp độ nâng cao
    └── quan_ly/                                 # Khảo sát cho quản lý
        ├── khao_sat_quan_ly_co_ban.md           # Cấp độ cơ bản
        ├── khao_sat_quan_ly_trung_binh.md       # Cấp độ trung bình
        └── khao_sat_quan_ly_nang_cao.md         # Cấp độ nâng cao
```

## Nội dung chính

### 5 Dimensions đánh giá cốt lõi

| Dimension | Weight | Mô tả |
|-----------|--------|-------|
| AI Knowledge | 15% | Kiến thức nền tảng về AI/ML |
| AI Application Skills | 20% | Kỹ năng ứng dụng, prompt engineering |
| Compliance & Risk | 25% | Tuân thủ quy định, quản lý rủi ro |
| Ethics & Data Privacy | 20% | Đạo đức AI, bảo mật dữ liệu |
| Self-Efficacy | 10% | Tự tin và sẵn sàng áp dụng AI |

### 4 Cấp độ năng lực

1. **Foundational** (0-49%): Nhận thức cơ bản
2. **Developing** (50-69%): Áp dụng có hỗ trợ
3. **Proficient** (70-84%): Áp dụng độc lập
4. **Advanced** (85-100%): Dẫn dắt sáng kiến AI

## Tài liệu tham khảo

- UNESCO AI Competency Framework for Teachers (2024)
- EU DigComp 2.2 (2022)
- WEF Future of Jobs 2025
- MAILS - Meta AI Literacy Scale (Carolus et al., 2023)
- AILS - Artificial Intelligence Literacy Scale (Wang et al., 2023)
