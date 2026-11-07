# Công cụ hồ sơ nhật ký mã số vùng trồng (MSVT)

Công cụ chạy trên trình duyệt, không cần cài đặt, để lập bộ hồ sơ mã số vùng trồng sầu riêng xuất khẩu Trung Quốc từ file Excel xuất từ Agribase:

- 5 nhật ký song ngữ Việt – Trung (canh tác, sâu bệnh, phân thuốc, bẫy/điều tra, ra vào vườn).
- 06 Bảng câu hỏi vùng trồng (种植场调查表) theo cấu trúc các hồ sơ đã được duyệt, kèm Phụ lục 1 (ảnh minh họa, nhật ký điện tử có mã QR) và Phụ lục 2 (ảnh vệ tinh từng lô có ranh giới lô).

## Cách dùng

1. Mở trang công cụ (GitHub Pages của repo này).
2. Nhập file Excel vùng trồng (3 sheet: Vùng trồng, Nông hộ, Lô đất), hoặc nhập nguyên bộ hồ sơ MVT dạng .zip (file Word “Bộ hồ sơ MVT”, tờ khai từng hộ, ảnh địa chính từng lô đặt tên “Ảnh địa chính Họ tên - Mã lô.jpg”). Ảnh địa chính được gán tự động vào Phụ lục 2 của bảng câu hỏi.
3. Nhập kết quả kiểm tra thực tế, chỉnh phiếu khảo sát, tải ảnh, rồi tải hồ sơ (.docx / .zip).

## Mẫu quy trình có sẵn

- Quy trình Đắk Lắk: vụ từ 01/09, 8 giai đoạn (mặc định).
- Quy trình Buôn Hồ: vụ từ 01/11, 9 giai đoạn theo nhật ký HTX Đoàn Kết Buôn Hồ; tự áp dụng cho vùng ở Buôn Hồ.

Chọn ở tab 2, ô "Áp dụng mẫu quy trình…".

## Quy trình riêng của doanh nghiệp

Tab Quy trình > “Tải quy trình ra Excel” cho file mẫu đã điền sẵn quy trình hiện tại (mùa vụ, giai đoạn, vật tư, công việc, sâu bệnh, diễn biến mẫu, bẫy). Sửa theo quy trình của doanh nghiệp rồi “Nhập quy trình từ Excel”: công cụ kiểm tra liên kết mã, báo lỗi và lưu ý trước khi áp dụng cho xã/phường.

## Xuất nhật ký canh tác sang FarmBase

Tab 3, thẻ "Xuất nhật ký canh tác sang FarmBase": chọn file NKCT xuất từ FarmBase của đúng vùng và mùa vụ, rồi tải file nhập theo mẫu 15 cột của FarmBase (dòng mới để trống ID). Chỉ gồm việc đến hôm nay và các lần kiểm tra đã nhập kết quả thực tế.

## Lưu ý về dữ liệu

- Dữ liệu và ảnh được lưu trên trình duyệt của máy đang dùng (IndexedDB), không gửi lên máy chủ. Máy khác hoặc trình duyệt khác sẽ không thấy.
- Dùng mục Sao lưu JSON để chuyển dữ liệu sang máy khác (ảnh không nằm trong file sao lưu).
- Kết quả bẫy và sâu bệnh chỉ lấy từ số liệu người dùng nhập; hồ sơ còn dùng dữ liệu mẫu sẽ in chữ BẢN NHÁP.
