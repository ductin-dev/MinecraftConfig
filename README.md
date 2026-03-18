# MinecraftConfig

## ✅ Quick way! (1.20.1)

Cách cài nhanh cho người mới:

1. ⭐ Cài đặt TLauncher: https://tlauncher.org/en
2. ⭐ Mở TLauncher, nhập username của bạn, sau đó bấm vào nút bên dưới.
   ![Open launcher menu](https://github.com/ductin-dev/MinecraftConfig/assets/59552083/e95829b7-c7db-461a-80da-5e1d6ccff98c)
3. ⭐ Bấm `Create`, chọn phiên bản như hình bên dưới, rồi xác nhận tạo.
   ![Select version](assets/quick-way-select-version.png)
4. ⭐ Sau khi tạo xong, bấm vào mũi tên để mở danh sách version.
   ![Open version list](assets/quick-way-version-list.png)
5. ⭐ Chọn icon chỉnh sửa, chờ popup hiện lên, rồi bấm `Mở thư mục mod pack`.
   ![Edit version](assets/quick-way-edit-icon.png)
6. ⭐ Chờ popup hiện lên, rồi bấm `Mở thư mục mod pack`.
   ![Open mod pack folder](assets/quick-way-open-modpack-folder.png)
7. ⭐ Copy mod vào đúng thư mục của version vừa tạo.
   ![Version mod folder](assets/quick-way-version-mod-folder.png)
8. ⭐ Bấm `Bắt đầu chơi`, `Enter the game`, hoặc `Install` (nút vàng).
9. ⭐ Vào `Multiplayer` và dùng thông tin kết nối được cung cấp trong nhóm chat để vào server.

Lưu ý:

- TLauncher có thể có 2 thư mục mod: một thư mục dùng chung cho toàn game và một thư mục riêng cho từng version.
- Nếu bạn đang dùng Fabric, hãy bỏ mod vào thư mục mod của version vừa tạo.
- Copy xong là hoàn tất phần cài đặt mod.

## Configuration

- Server hostname: `minecraft.mrsatdev.com`
- Phiên bản Minecraft hiện tại: `1.21.11`
- Mod engine hiện tại: `Fabric 0.18.4`
- Java khuyến nghị: `Java 21.0+`
- RAM khuyến nghị: `4GB+`

### Additional settings

- Mods: Mặc định sẽ bật toàn bộ mods. Không nên cài thêm hoặc chỉnh nhiều vì dễ mất tương thích với phiên bản Minecraft và mod engine hiện tại.
- Resource pack: Một số resource pack cần bật thủ công trong menu `Resource Pack`. Đây chỉ là phần hiển thị phía máy của bạn, không ảnh hưởng tới server.
  ![Resource pack menu](./assets/image-20240519161014-1.png)
- Shader: Có thể tùy chỉnh theo cấu hình máy. Hiện tại hệ thống đang dùng `Iris Shader`, bạn có thể vào `Tùy chọn hình ảnh` trong game để chỉnh.

## Mod List

## Resource-packs List

Glowing (Optional)

Hyper realistic sky (Optional)

## Shader List

RedHat Shaders v34.0 (Optional)

---

# MinecraftConfig OPTION B

## Connect Guide: Connect linux server (For server mods)

1. Cài đặt TLaucher: https://tlauncher.org/en
2. Khởi động TLaucher, chọn phiên bản `1.20.1 Forge Optifine` (with forge `47.0.45`)
3. Khởi động Minecraft -> Chọn `Multiplayer` -> `Add a Server`
4. Kết nối đến server trong nhóm chat và bắt đầu game

![Server connect](https://github.com/ductin-dev/MinecraftConfig/assets/59552083/9ac7cf5f-e5d1-4644-bd6c-51310b4a9346)

## Install Mods

Khi kết nối tới server sẽ có thông báo lỗi nếu thiếu hoặc dư mod, để khắc phục:

1. Ấn `Open Mod Folder`
2. Pull thư mục `mods` ở GitHub này và copy hoặc replace toàn bộ vào thư mục trên máy
3. Vào lại game

## Install Plugins

Phiên bản hiện tại không có plugin nào.

## UI and Client Enhancement

- Server resource pack: None
- Shader: customize with shader version `47.0.45`
- Custom soundpack: None

---

# Admin section

## Install Guide (for Detached server)

- Using `docker-compose.yml`

## Install for LAN server

- Run minecraft instance on `modrinth` app
- Use the latest `xxx.mrpack` file in the `mrpack` folder to import server settings, mods, resource pack, etc.

## Install Guide (for Forge Client) [OPTIONAL]

- Cài đặt Forge tại thư mục `./assets/forge-<version>-installer.jar`
- Khởi động TLaucher, tại menu chọn version, chọn phiên bản Forge vừa cài đặt và nhấn `Install > Enter the game`
- Khi game khởi động xong, chọn `Mod > Open Mod Folder`
- Copy toàn bộ file ở thư mục `./mods/` vào trong thư mục mod của game vừa được mở
- Khởi động lại game

## Resource Pack + Shader (For 3D & RTX) [OPTIONAL]

- Copy thư mục `resourcepacks` và `shaderpacks` vào thư mục game
- Vào thư mục `./resourcepacks/..` và giải nén toàn bộ thư mục con bên trong. Không cần giải nén thư mục `shaderpacks`
- Khởi động game và vào menu resource pack để chọn pack phù hợp, tương tự với shader
