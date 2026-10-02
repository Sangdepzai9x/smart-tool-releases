# Smart Tool Windows

Kho nay chi chua ban phat hanh Windows va huong dan cap nhat. Ma nguon va du lieu tai khoan khong duoc dang len day.

## Chon ban

- **login**: co dang nhap va license.
- **unified**: chay truc tiep, khong qua man hinh dang nhap.

Tai goi ZIP tu [Releases](https://github.com/Sangdepzai9x/smart-tool-releases/releases/latest). Khong tai cac goi Source code ZIP/TAR tu GitHub de cai ung dung.

## Nang cap ban cu lan dau

1. Dong Smart Tool cu va cac browser do tool mo.
2. Tai **Nang-cap-SmartTool.cmd** va **Nang-cap-SmartTool.ps1** trong release, dat cung thu muc.
3. Chay file CMD, chon thu muc chua EXE ban cu. Script tu tai dung loai, kiem tra chu ky/checksum, nang cap va mo lai tool.
4. Giu nguyen du lieu cu; khong can copy cac bang cau hinh sang thu muc moi.

Tu ban 1.2.1, tool co nut **Cap nhat tool** va tuy chon **Tu cap nhat**. Tool tai ban moi o nen, cho Monitor/Edit/Upload va cac tac vu kiem tra ket thuc, roi cai va khoi dong lai.

Du lieu cau hinh duoc luu tai `%LOCALAPPDATA%\SmartUnifiedTool`. Ban truoc duoc giu trong thu muc `.smart-update-backup-...` canh thu muc cai. Neu mat dien giua cap nhat, chay `Recover-update.cmd` trong `%LOCALAPPDATA%\SmartUnifiedTool\updates\<ma cap nhat>` truoc khi mo lai tool.

Cac ban cu chua co updater can nang cap mot lan bang script tren. Sua source khong tu tao release: can build, kiem tra goi sach va ky manifest truoc khi dang ban moi.
