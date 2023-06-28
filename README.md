GBA.js
======
**Phiên bản 1.0 Release Candidate 1 - Bản quyền © 2012 - 2013 Jeffrey Pfau**

GBA.js là một bộ giả lập Game Boy Advance được viết từ đầu để sử dụng các công nghệ HTML5 như Canvas và Web Audio. Nó không sử dụng các plugin và được thiết kế để chạy trên các trình duyệt web hiện đại. Nó được lưu trữ [trên GitHub](https://github.com/endrift/gbajs) và được cung cấp dưới giấy phép BSD 2 điều khoản. Phiên bản mới nhất có thể được tìm thấy tại [http://endrift.github.io/gbajs/](http://endrift.github.io/gbajs/).

## Tương thích với trình duyệt
Phiên bản hiện tại của GBA.js được biết là hoạt động trên các trình duyệt web sau đây:

* Safari 6.0 trở lên
* Chrome 22 trở lên
* Firefox 25 trở lên (chạy chậm)

Các trình duyệt web sau đây cũng hoạt động, nhưng sẽ có các tập hợp tính năng bị giảm chất lượng:

* Firefox 15 trở lên (không âm thanh, chạy chậm)
* Opera 12.1x trở lên (không âm thanh, chạy chậm)
* Internet Explorer 10 trở lên (không âm thanh, chạy chậm, hiển thị pixelated không hoạt động)
* Chrome 20, 21 (hiển thị pixelated không hoạt động)

Các trình duyệt web sau đây sẽ không hoạt động:

* Safari 5.1.x hoặc cũ hơn (không có File API để tải lên trò chơi vào JavaScript)
* Firefox 14 hoặc cũ hơn (không có DataView, được sử dụng cho bộ nhớ)
* Internet Explorer 9 hoặc cũ hơn

Tất cả các trình duyệt web khác chưa được kiểm tra.

## Tương thích với trò chơi
Vui lòng xem [danh sách tương thích trên wiki của GitHub](https://github.com/endrift/gbajs/wiki/Compatibility-List) để biết danh sách các trò chơi đã được kiểm tra. Lưu ý rằng GBA.js được điều chỉnh cho các trò chơi thương mại và hiện vẫn chưa hỗ trợ tốt cho các trò chơi tự làm.

## Danh sách tính năng
Hiện tại, mọi phần của phần cứng Game Boy Advance, ngoại trừ một số tính năng ít được sử dụng và cáp kết nối, đã được cài đặt.

Bộ giả lập cũng có các tính năng sau:

* Tải và tải lên savegame
* Chụp màn hình
* Tạm dừng giả lập
* Hỗ trợ gamepaks chứa đồng hồ thời gian thực (ví dụ: Pokemon Ruby và Sapphire)

Các tính năng có thể được cài đặt trong tương lai bao gồm:

* Lưu trạng thái
* Điều khiển có thể thay đổi
* Hỗ trợ bộ điều khiển gamepad
* Cáp kết nối thông qua Web Sockets
* Hỗ trợ mã cheat
* Hỗ trợ toàn màn hình
* Hỗ trợ gamepaks có các cảm biến khác (ví dụ: WarioWare Twisted!, Boktai)

## License
Bản quyền © 2012 - 2013, Jeffrey Pfau
Tất cả các quyền được bảo lưu.

Việc phân phối và sử dụng trong các dạng mã nguồn và nhị phân, có hoặc không có sửa đổi, được phép miễn là các điều kiện sau được đáp ứng:

* Việc phân phối mã nguồn phải giữ lại thông báo bản quyền trên và danh sách các điều kiện và từ từ từ chối phía trên.

* Việc phân phối dưới dạng nhị phân phải sao chép lại thông báo bản quyền trên, danh sách các điều kiện và từ từ từ chối phía trên trong tài liệu và / hoặc các tài liệu khác đi kèm với phân phối.

PHẦN MỀM NÀY ĐƯỢC CUNG CẤP BỞI CHỦ SỞ HỮU BẢN QUYỀN VÀ CỘNG TÁC VIÊN "NHƯ VẬY" VÀ BẤT KỂ BẤT KỲ BẢO HÀNH RÕ RÀNG HOẶC NGỤ Ý NÀO, BAO GỒM, NHƯNG KHÔNG GIỚI HẠN, CÁC BẢO HÀNH VỀ CHẤT LƯỢNG HỢP LÝ VÀ TƯƠNG THÍCH VỚI MỘT MỤC ĐÍCH CỤ THỂ NÀO ĐÓ ĐƯỢC TỪ CHỐI. TRONG BẤT KỲ TRƯỜNG HỢP NÀO, CHỦ SỞ HỮU BẢN QUYỀN HOẶC CỘNG TÁC VIÊN SẼ KHÔNG CHỊU TRÁCH NHIỆM CHO BẤT KỲ THIỆT HẠI TRỰC TIẾP,
