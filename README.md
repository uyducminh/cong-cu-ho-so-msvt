# Công cụ hồ sơ nhật ký mã số vùng trồng (MSVT)

Công cụ chạy trên trình duyệt, không cần cài đặt, để lập bộ hồ sơ mã số vùng trồng sầu riêng xuất khẩu Trung Quốc từ file Excel xuất từ Agribase:

- 5 nhật ký song ngữ Việt – Trung (canh tác, sâu bệnh, phân thuốc, bẫy/điều tra, ra vào vườn).
- 06 Bảng câu hỏi vùng trồng (种植场调查表) theo cấu trúc các hồ sơ đã được duyệt, kèm Phụ lục 1 (ảnh minh họa, nhật ký điện tử có mã QR) và Phụ lục 2 (ảnh vệ tinh từng lô có ranh giới lô).

## Cách dùng

1. Mở trang công cụ (GitHub Pages của repo này).
2. Nhập file Excel vùng trồng (3 sheet: Vùng trồng, Nông hộ, Lô đất), hoặc nhập nguyên bộ hồ sơ MVT dạng .zip (file Word “Bộ hồ sơ MVT”, tờ khai từng hộ, ảnh địa chính từng lô đặt tên “Ảnh địa chính Họ tên - Mã lô.jpg”). Ảnh địa chính được gán tự động vào Phụ lục 2 của bảng câu hỏi.
3. Nhập kết quả kiểm tra thực tế, chỉnh phiếu khảo sát, tải ảnh, rồi tải hồ sơ (.docx / .zip).

## Lưu ý về dữ liệu

- Dữ liệu và ảnh được lưu trên trình duyệt của máy đang dùng (IndexedDB), không gửi lên máy chủ. Máy khác hoặc trình duyệt khác sẽ không thấy.
- Dùng mục Sao lưu JSON để chuyển dữ liệu sang máy khác (ảnh không nằm trong file sao lưu).
- Kết quả bẫy và sâu bệnh chỉ lấy từ số liệu người dùng nhập; hồ sơ còn dùng dữ liệu mẫu sẽ in chữ BẢN NHÁP.
