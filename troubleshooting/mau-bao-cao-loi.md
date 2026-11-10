# Kỹ năng Tra cứu & Mẫu Báo Cáo Lỗi (Bug Report)

## 1. Kỹ năng Tự Tra cứu (Search Operators)
- `site:stackoverflow.com "lỗi cụ thể"`: Tìm lỗi chính xác trên một trang.
- Dấu `""`: Tìm kiếm chính xác cụm từ.
- Dấu `-`: Loại trừ từ khóa (VD: `python error -django`).
- Đọc StackOverflow: Ưu tiên câu trả lời có tích xanh (Accepted) và Upvote cao, kiểm tra ngày đăng (< 5 năm).

## 2. Prompt AI 3 thành phần (Khi hỏi ChatGPT/Claude)
1. **Ngữ cảnh:** "Tôi đang viết code ReactJS kết nối với API..."
2. **Lỗi nguyên văn:** "Nhận được mã lỗi: [Copy nguyên dòng log lỗi]"
3. **Yêu cầu:** "Hãy giải thích lỗi này và đưa ra cách khắc phục."

## 3. Mẫu Bug Report 4 Bước (Bug Reporting Framework)
Khi nhờ IT hỗ trợ, vui lòng điền theo mẫu sau, không nhắn tin mù mờ "bị lỗi rồi":

- **Context (Ngữ cảnh):** Đang làm gì, ở môi trường nào (Browser gì, version bao nhiêu, link nào).
- **Expected (Kết quả mong đợi):** Nút Submit bấm vào sẽ lưu dữ liệu.
- **Actual (Kết quả thực tế):** Nút Submit không phản hồi, trang bị treo.
- **Log/Screenshot:** (Đính kèm ảnh chụp màn hình toàn bộ lỗi hoặc copy log từ tab Console F12).
