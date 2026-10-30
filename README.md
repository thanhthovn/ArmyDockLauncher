# Army Dock

Launcher Android TV giao diện tối, tông xanh quân đội, điều khiển bằng remote. Đây là dự án Android Studio độc lập; chưa sửa repository CleanYourTV.

## Tính năng trong bản đầu

- Quét các ứng dụng có thể khởi chạy trên TV và hiển thị biểu tượng trong dock ngang căn giữa, nền kính xanh olive bán trong suốt.
- Icon Army Dock tông xanh olive, tối ưu hiển thị trên Android TV.
- Banner Android TV ngang theo cùng nhận diện Army Dock, có tên app để hiển thị trên màn hình chính TV.
- Hình nền mặc định là gradient xanh quân đội nhẹ, không đóng gói ảnh đua thuyền. Cài đặt Army Dock > Đổi hình nền có lựa chọn ảnh từ thiết bị hoặc nhập URL HTTPS trực tiếp đến ảnh (tối đa 20 MB). Ảnh URL được lưu trong thư mục riêng của app (`files/wallpaper/launcher-wallpaper.img`); vẫn còn sau khi khởi động lại launcher và bị xóa khi khôi phục hình nền mặc định hoặc chọn ảnh khác từ thiết bị.
- Dock dạng kính tự căn chiều ngang theo số ứng dụng, co gọn khi ít app và chỉ cuộn khi danh sách dài hơn màn hình; tile dùng banner TV theo đúng tỉ lệ, bo góc nhẹ 10dp và có viền xanh lá nhạt khi được focus. Độ phóng và độ nhấc khi focus có thể chỉnh trong Cài đặt hiển thị, mặc định 8% và 4dp.
- Chiều cao dock tự điều chỉnh theo độ phóng/độ nhấc focus để chừa đủ chỗ cho tile đang được chọn. Thanh nút theo thứ tự Wi‑Fi, Nguồn vào, Ứng dụng, Cài đặt; bốn nút dùng nền trong suốt, chỉ nút được focus sáng rõ. Cụm tự co giãn theo SSID/tên nguồn vào. Nút **Ứng dụng** mở bảng giữa màn hình, nền chỉnh trong suốt, nhóm TV/di động và lưới 5 app mỗi hàng; các ô app không có nền, chỉ có viền khi focus. Nhấn OK để mở app và giữ OK để xác nhận rồi mở trình gỡ cài đặt Android.
- Nhấn **OK** để mở ứng dụng.
- Khi launcher mở, focus ban đầu đặt lên ứng dụng đầu tiên trong dock; nhấn **lên** từ dock sẽ chuyển focus sang nút Cài đặt.
- Nhấn **lên** để chuyển focus từ dock lên thanh nút; nhấn giữ **lên** để vào chế độ sắp xếp, dùng trái/phải đổi vị trí rồi nhấn **OK** để hoàn tất. Hướng dẫn chỉ hiện trong dock khi chế độ đang hoạt động.
- Nhấn giữ **xuống** để mở menu gọn có icon và tên ứng dụng; chọn ẩn hoặc thêm app đang ẩn. Sau đó nhấn **lên** để hoàn tất. Lựa chọn được lưu trên thiết bị.
- Cụm đồng hồ/ngày tháng nằm đầu màn hình, số giờ lớn hơn 5%, có vạch ngăn dọc, khoảng cách giờ và ngày được nới nhẹ, thẻ rộng 105% chiều rộng tự nhiên. Thứ hiển thị chữ hoa có ký tự trang trí; ngày dương theo dạng “▣ Ngày 26 Tháng 10 Năm 2026”; ngày âm theo dạng “☾ Mồng 16 Tháng Mười Một”; dòng can chi viết hoa có ký tự trang trí. Bên dưới là vị trí/thời tiết với icon ghim trắng, tên địa phương trước thông tin thời tiết, chữ đậm viền cam cỡ 17sp và không có nền riêng. Cụm CPU/RAM/ROM được căn giữa sát đáy bên dưới dock, chữ cỡ 75% và có viền nâu. Trong **Cài đặt hiển thị** có thể bật/tắt hai cụm; tắt thời tiết sẽ dừng truy vấn mạng, còn CPU/RAM/ROM chỉ cập nhật mỗi 10 giây khi đang bật. Ngày và giờ theo múi giờ Bangkok.
- Có thể chọn tỉnh/thành, xã/phường trong Cài đặt từ danh sách địa danh Việt Nam được đóng gói trong ứng dụng, gồm 34 tỉnh/thành và 3.321 đơn vị cấp xã; tìm kiếm hỗ trợ dấu tiếng Việt hoặc không dấu. Thời tiết hiện nhiệt độ, tình trạng hiện tại và tên khu vực, tự cập nhật khoảng 30 phút một lần. Chọn vị trí thủ công, không yêu cầu quyền GPS. Cần internet để lấy thời tiết từ Open-Meteo.
- Thông tin launcher hiển thị Army Launcher, phiên bản, Design by Thánh Thơ, Weather: Open-Meteo, số điện thoại 0984.394.494 và (c) 2026; không còn dòng Lite version hay dòng trống.
- Nút Cài đặt nằm ngoài cùng bên phải: nhấn để mở cài đặt TV, nhấn giữ để mở menu cài đặt Army Dock cùng giao diện tối bo góc và focus bằng remote như menu ứng dụng. Menu tổng Cài đặt Army Dock được canh bên phải, ngang hàng với nút Cài đặt. Nhấn **lên** từ dock sẽ chuyển focus vào nút Cài đặt. Trong Cài đặt hiển thị, hai công tắc bật/tắt cụm thông tin luôn nằm đầu danh sách; các thanh chỉnh độ trong suốt, độ phóng và độ nhấc nằm bên dưới. Độ trong suốt dock, cụm ngày giờ và menu Ứng dụng mặc định lần lượt 75%, 30%, 5%; độ phóng tile mặc định 8% và độ nhấc khi focus mặc định 4dp. Mục “Khôi phục mặc định” hỏi xác nhận trước khi đặt lại dock, hình nền, độ trong suốt và hiệu ứng focus. Nút mạng báo Wi‑Fi/SSID hoặc Ethernet; Android có thể yêu cầu quyền vị trí để hiện SSID.
- Các nút trên cùng có hiệu ứng focus nhẹ: phóng lớn rất ít, giữ nguyên vị trí và làm viền sáng hơn. Trong Cài đặt hiển thị, từng hàng slider được bo nền sáng rõ khi focus; chữ và công tắc của hai hàng bật/tắt được căn giữa theo chiều dọc.
- Cửa sổ launcher vẽ tràn mép màn hình với system bars trong suốt để tránh dải đen sát cạnh trên/dưới.

## Mở và cài

Mở thư mục này bằng Android Studio (JDK 17, Android SDK 35), chờ Gradle đồng bộ rồi chạy cấu hình `app` lên Android TV/Google TV. Có thể build APK bằng Android Studio hoặc `gradlew.bat assembleDebug` trong thư mục dự án.

Ứng dụng yêu cầu Android 8.0 (API 26) trở lên, build bằng SDK 35 và target Android 15 (API 35). Army Dock đăng ký cả mục Android TV app và vai trò Home; sau khi cài, chọn Army Dock khi Android TV hỏi ứng dụng Home hoặc đổi tại cài đặt Home app/ứng dụng mặc định của TV (tên mục tùy hãng). Nếu chưa chọn làm Home, app vẫn mở được từ danh sách ứng dụng.

## Giới hạn theo hãng

Nút Nguồn vào dùng trạng thái TV passthrough inputs và intent Android TV chuẩn; một số firmware không công khai HDMI cho launcher bên thứ ba, khi đó nút chỉ hiện icon và cần chọn nguồn bằng remote. Android cung cấp trạng thái kết nối của từng TV input nhưng không phải TV nào cũng cho ứng dụng bên thứ ba biết nguồn nào đang được chọn. Tên Wi‑Fi cần quyền vị trí và dịch vụ vị trí đang bật; nhấn nút mạng để cấp quyền nếu được hỏi. Tile “Màn hình chính” được đổi nhãn và icon trong Army Dock; điều này không đổi tên/icon ứng dụng hệ thống TV.
