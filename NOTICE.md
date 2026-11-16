# NOTICE

**dBot © 2026 Phạm Duy** — liên hệ https://fb.com/neull

dBot phát hành theo giấy phép **GNU Affero General Public License v3.0** (AGPL-3.0-or-later), toàn văn trong `LICENSE`. Ai nhận dBot đều có quyền nhận mã nguồn tương ứng, sửa và phát hành lại theo cùng giấy phép.

## Dựa trên

dBot là bản sửa đổi của [OasisBot / RSBot](https://github.com/Silkroad-Developer-Community/OasisBot) (commit `2de35dae27cc7c043fdf5a448ff1528e5a55b820`).
Copyright © 2018–2026 RSBot Team; 2026 Silkroad Developer Community và những người đóng góp.
Ghi công, README và thông báo bản quyền gốc được giữ nguyên trong bản mã nguồn; giấy phép gốc là AGPL-3.0, giữ nguyên trong `LICENSE`.
Thư viện giao diện SDUI và các thành phần khác giữ giấy phép riêng của chúng; xem `THIRD_PARTY_NOTICES.md`.

## Phần do dBot viết mới

- Thư mục `Application\OasisBot\Dbot` (tài khoản dBot, giao diện, tự động hóa, khôi phục, cập nhật…).
- Các trang và cửa sổ `Dbot*` và các phần `Main.*.cs` mới trong `Application\OasisBot\Views` (Quản lý tài khoản, Đăng nhập dBot, Chiến đấu, Khởi đầu, Phiên…).
- Các thành phần mới trong `Library\RSBot.Core\Components` (nhiều tài khoản, acc farm, đội hình, khôi phục bot, cảnh báo mục tiêu, sắp xếp túi…) và `Library\RSBot.Core\Network\Tcvn3.cs`.
- Các trang và gói tin mới trong plugin: Thông báo/Telegram (Chat), Quầy hàng (Inventory), Chế tạo và Lọc vật phẩm (Items), Bang hội (Party), Mật khẩu cấp 2 và đăng ký (General), Thông tin (Statistics), tương thích phBot (Python), và các phần mới của Trade, Training, Lure, Alchemy, Protection, Skills.
- Bộ kiểm thử trong `tests` và các kịch bản build/đóng gói/phát hành của dBot trong `scripts` (`build.ps1`, `dBot.iss`, `build-installer.ps1`, `publish-release.ps1`).

Các file `.cs` do dBot tạo mới có dòng đầu `// dBot - Copyright (C) 2026 Phạm Duy. AGPL-3.0-or-later.`. Các file gốc của OasisBot/RSBot chỉ được sửa thì giữ nguyên thông báo bản quyền gốc và không mang dòng này.

dBot không dùng che mã, chống gỡ lỗi hay bất kỳ cơ chế nào ngăn người nhận dùng mã nguồn.
