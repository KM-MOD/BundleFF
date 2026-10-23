# KM MOD FF — eff

Kho file donor (eff) cho bot KM MOD FF. Bot tự đọc nội dung từng file và chỉ tải
những file mà bộ đồ đang build cần, nên **vị trí thư mục không quan trọng**.

## Cấu trúc
- `<Loại>/<Tên Đồ>/` — file chỉ món đó dùng.
- `Chung/` — file dùng chung cho nhiều món (shaders.*, texture chung, bundle của skin mà nhiều món cùng lấy).
- `Khác/` — file hiện chưa món nào dùng (để dành).

## Thêm đồ mới
Tạo thư mục `<Loại>/<Tên Đồ>/`, chép file `optionalab_...` gốc của game vào (giữ nguyên tên),
commit + push. Bot nhận file mới ở lần build sau (tối đa ~10 phút).

Không đổi tên file. Không cần chép lại file đã có trong `Chung/`.

## Món hiện có
- `Accessory/Nạ Chiến Thần` (chỉ dùng file trong `Chung/`)
- `Accessory/Nạ Chiến Thần Dung Nham` (chỉ dùng file trong `Chung/`)
- `Bottom/Quần Nagi` (chỉ dùng file trong `Chung/`)
- `Bottom/Quần Thám Hiểm`
- `Bottom/Quần Vệ Binh Tinh Tú` (chỉ dùng file trong `Chung/`)
- `Fist/Băng Quyền` (chỉ dùng file trong `Chung/`)
- `Fist/Chidori`
- `Fist/Hoả Quyền` (chỉ dùng file trong `Chung/`)
- `Fist/Hắc Ảnh`
- `Fist/Hỗn Mang` (chỉ dùng file trong `Chung/`)
- `Fist/Kính Đình Quyền`
- `Fist/Long Quyền` (chỉ dùng file trong `Chung/`)
- `Fist/Lôi Xích Quyền`
- `Fist/Nhất Quyền` (chỉ dùng file trong `Chung/`)
- `Hair/Tóc Hắc Tinh`
- `Hair/Tóc Mộng Cảnh` (chỉ dùng file trong `Chung/`)
- `Hair/Đầu Đạo Sĩ` (chỉ dùng file trong `Chung/`)
- `Head/Mắt Tia Chớp`
- `Top/Áo Biker`
- `Top/Áo Bóng Đá`
- `Top/Áo Cyborg` (chỉ dùng file trong `Chung/`)
- `Top/Áo Cầu Thủ Tay Dài`
- `Top/Áo Hắc Tinh`
- `Top/Áo Itachi`
- `Top/Áo Ma Vương Hồng Điệp`
- `Top/Áo Nagi` (chỉ dùng file trong `Chung/`)
- `Top/Áo Nero`
- `Top/Áo Quái Nhân Hư Không`
- `Top/Áo Quỷ Lửa`
- `Top/Áo Sasuke`
- `Top/Áo Thích Khách`
- `Top/Áo Thế Phiệt` (chỉ dùng file trong `Chung/`)
- `Top/Áo Thỏ Neon` (chỉ dùng file trong `Chung/`)
- `Top/Áo Vô Diện Lôi Thần`
- `Top/Áo Vệ Binh Tinh Tú` (chỉ dùng file trong `Chung/`)
- `Top/Áo Ác Nhân Bọ Cạp` (chỉ dùng file trong `Chung/`)
