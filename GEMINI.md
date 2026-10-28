# Quy Tắc Chỉnh Sửa Code & Tối Ưu Tài Nguyên (Coding Guidelines)

## 1. Sửa trực tiếp & Nhắm trúng mục tiêu (Surgical Edits Only)
- Khi chỉnh sửa hoặc cập nhật tính năng, chỉ can thiệp trực tiếp vào đúng các dòng, hàm hoặc khối code liên quan.
- TUYỆT ĐỐI KHÔNG viết lại toàn bộ file từ đầu, không tự ý tái cấu trúc (refactor) các phần không được yêu cầu.

## 2. Giữ nguyên vẹn mã nguồn hiện có (Preserve Existing Code)
- Giữ nguyên 100% logic đang chạy ổn định, các hàm hỗ trợ, giao diện CSS, và định dạng văn bản.
- Bảo vệ nghiêm ngặt tính toàn vẹn của mã hóa tiếng Việt UTF-8, tránh gây lỗi font chữ.

## 3. Tiết kiệm tài nguyên & Dung lượng Token (Resource Efficiency)
- Chỉ làm đúng và đủ phần việc được yêu cầu, tránh lãng phí thời gian và token.
- Không in lại toàn bộ file mã nguồn dài vào tin nhắn chat nếu không có yêu cầu cụ thể từ người dùng.
