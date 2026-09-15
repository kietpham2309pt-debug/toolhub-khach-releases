# ToolHub — bản cài cho khách hàng

ToolHub là xưởng dữ liệu sản phẩm cho nhà bán hàng: cào giá thị trường, cào thông tin sản phẩm theo nhóm hàng,
ảnh nền trắng, xoá phông và theo dõi giá đối thủ. Mọi dữ liệu nằm trên máy bạn.

Kho này chỉ chứa **bản cài đặt**. Để dùng app bạn cần **tài khoản cửa hàng do nơi bán cấp**
(tên đăng nhập + mật khẩu tạm).

## Tải về

Vào mục **[Releases](../../releases/latest)** và tải đúng bản cho máy của bạn:

| Máy | Tệp | Dung lượng |
|---|---|---|
| Windows 10 / 11 (64-bit) | **`ToolHub-Windows-<phiên bản>.zip`** | ~1 GB |
| Mac chip Apple (M1, M2, M3, M4…) | **`ToolHub-macOS-<phiên bản>.dmg`** | ~1 GB |

Bên cạnh mỗi tệp có mã SHA-256 (`.sha256`) để đối chiếu tệp tải về không bị hỏng. Các tệp đuôi
`-capnhat.zip` và `manifest*.json` là gói app **tự tải** khi cập nhật — bạn không cần tải chúng.

## Máy cần có

- **Windows**: Windows 10/11 64-bit, RAM 8 GB, còn trống 4 GB ổ đĩa.
- **macOS**: máy Mac chip Apple, **macOS 14 trở lên**, RAM 8 GB. Bản macOS **không** chạy trên Mac chip Intel.
- Cả hai: cài **Google Chrome** (ToolHub dùng Chrome để cào giá Google Shopping), có mạng lúc đăng nhập.

## Cài đặt

**Windows**
1. Giải nén tệp `.zip` ra ổ đĩa (ví dụ `D:\ToolHub`) — đừng để trong `Program Files`.
2. Mở thư mục `toolhub` rồi chạy `toolhub.exe`. Không phải cài thêm gì.
3. Đọc `DOC-TRUOC-KHI-DUNG.txt` trong gói để biết cách đăng nhập và các việc nên làm lần đầu.

**macOS**
1. Mở tệp `.dmg`, kéo **ToolHub** vào thư mục **Applications**.
2. Lần đầu mở, macOS sẽ báo không mở được vì bản này chưa được Apple chứng nhận:
   bấm **Xong**, vào **Cài đặt hệ thống → Quyền riêng tư & Bảo mật**, kéo xuống bấm **Vẫn mở**, nhập mật khẩu máy.
   Từ lần sau nhấp đúp là mở.
3. Chi tiết trong tệp `HUONG DAN CAI DAT.txt` bên trong `.dmg`.

## Cập nhật

**Bạn không phải cài lại.** Mỗi lần mở app, ToolHub (cả Windows lẫn macOS) tự kiểm tra bản mới, tự tải
phần thay đổi (vài chục MB), rồi đếm ngược 15 giây và tự cài, tự mở lại — có nút «Để sau» nếu đang dở tay.
Đang chạy cào thì app chờ tới lần mở sau mới cài. Dữ liệu của bạn luôn giữ nguyên.

- **macOS**: để app tự cập nhật được, hãy chạy ToolHub từ thư mục **Applications** (không mở thẳng từ
  thư mục Tải về hay từ đĩa `.dmg`). Nếu không tự cài được, app sẽ báo rõ lý do và cách xử lý.

## Tài khoản & hỗ trợ

Quên mật khẩu, đổi máy, gia hạn hay nâng gói: liên hệ nơi đã bán ToolHub cho bạn và gửi kèm **mã máy**
(hiện ở màn đăng nhập, bấm vào để chép).
