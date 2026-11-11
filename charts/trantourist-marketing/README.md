# Trantourist Marketing

Org chart cho phòng Marketing Công ty TNHH Trần Gia Phú Thái, theo đúng định dạng repo agent-org-chart.

```
Leader (điều phối)
├── Digital Marketing
├── Editor & Content
├── Data (FDI/Mailchimp/LinkedIn)
├── GEO/AI
├── Content Writer
└── Content Creator (Audio Voice)
```

## Cách dùng

1. Đưa `chart.json` cho agent của bạn (Claude, Grok Bot...) kèm câu: `Import chart.json này, dùng agent hiện tại làm Leader.`
2. Hoặc fork repo, thêm thư mục này vào `charts/`, rồi: `Import trantourist-marketing from https://github.com/<tài-khoản-của-bạn>/agent-org-chart`
3. Agent tạo/gán 7 vị trí, báo created/reused, rồi hỏi mục tiêu đầu tiên.

## Cần Leader chốt

- Vị trí duyệt content trước khi dựng (đang gán tạm cho Digital Marketing).
- Ngày chạy "Đo AI citation" và ngày chốt "Báo cáo KPI tháng".
- Persona hiện soạn từ quy trình đã mô tả; chỉnh lại cho khớp thực tế từng vị trí.
