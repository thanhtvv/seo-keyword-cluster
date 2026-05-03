# SEO Keyword Cluster Pro 🔍

Công cụ gom nhóm từ khóa SEO chuyên nghiệp với AI — chạy hoàn toàn trên trình duyệt, không cần server.

## ✨ Tính năng

- **Gom nhóm từ khóa** dựa trên SERP overlap (Serper.dev API)
- **Phân tích Search Intent** tự động (Informational / Transactional)
- **Tạo Outline AI** cho từng keyword — dùng Gemini API, ghi rõ H2/H3
- **Kiến trúc Silo** — phân tích cấu trúc nội dung theo nhóm cluster
- **Xuất Excel** — cluster + SERP data
- **Lưu trữ offline** — IndexedDB & LocalStorage
- Hỗ trợ **nhiều Serper API key** (tự động xoay vòng)

## 🚀 Sử dụng

Chỉ cần mở file `index.html` trên trình duyệt — không cần cài đặt gì thêm.

### Yêu cầu API Keys
- [Serper.dev](https://serper.dev) — Quét SERP Google (miễn phí 2,500 queries)
- [Google AI Studio](https://aistudio.google.com) — Gemini API Key (miễn phí)

## 🛠 Tech Stack

- Vanilla HTML/CSS/JavaScript (single file)
- Gemini API (streaming)
- Serper.dev API
- Jina.ai Reader (quét heading đối thủ)
- marked.js, SheetJS, Font Awesome

## 📄 License

MIT
