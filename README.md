# Web/app học tập — Hóa học 9, Bài 28

**Bài 28: Lipid**
Môn Khoa học tự nhiên 9 (phân môn Hóa học) — Chương trình GDPT 2018, sách Kết nối tri thức với cuộc sống.

Giáo viên: Lê Văn Thắng — Trường TH và THCS Phước Hưng, xã Nhơn Hội, tỉnh An Giang.

## Nội dung

Web/app học tập 6 phần: Khởi động, Khám phá, Mô phỏng, Sơ đồ tư duy, Luyện tập (10 câu trắc nghiệm tự chấm), Vận dụng.

Mô phỏng: Tính tan của chất béo (Trạm 2, SGK trang 129) — mỡ lợn (hoặc dầu ăn) trong nước cất và trong xăng, 4 bước theo đúng thứ tự, hình SVG thay đổi theo từng bước (ống nước: chất béo nổi lên trên, không tan; ống xăng: chất béo tan hoàn toàn).

Sơ đồ 4 bước làm xà phòng thủ công (trình bày có hình minh hoạ trong phần Khám phá); nhiệm vụ về nhà làm xà phòng từ dầu ăn thừa (cùng người lớn) trong phần Vận dụng.

## Cách dùng

- Mở file `index.html` bằng trình duyệt bất kì (không cần máy chủ).
- Học sinh đăng nhập bằng Họ tên + Lớp, học 6 phần, làm 10 câu trắc nghiệm rồi nộp bài.
- Trạng thái: CHỜ /exec — chưa có Web App URL (Google đang chặn tạo dự án Apps Script mới) nên điểm hiện chỉ lưu trên máy (localStorage). Khi có URL /exec, parent sẽ patch fetch vào file.

## Khóa đáp án

1B 2A 3C 4D 5B 6B 7A 8C 9C 10D

## File trong repo

- `index.html` — web/app hoàn chỉnh, tự chứa (hình ảnh nhúng base64).
- `Web_Hoc_Tap_Hoa9_Bai28.md` — bản sao toàn bộ mã nguồn kèm khóa đáp án.
- `Code.gs` — Apps Script ghi điểm về Google Sheets (tab KetQua); deploy sau khi Google mở lại việc tạo dự án.
- `assets-flow/` — 3 ảnh nền gốc (Gemini, 1376×768) + logo thầy Lê Văn Thắng.
