# BTL-LTNC - Jewel

1. GIỚI THIỆU GAME
   Jewel Castle là một trò chơi giải đố. Jewel Castle thách thức người chơi ghép các viên ngọc và tạo ra các combo. Đổi chỗ các viên ngọc, ghép ít nhất 3 viên ngọc lại với nhau và cố gắng đạt được số điểm cao nhất trong thời gian giới hạn!!!

2. CHƠI GAME
   Sau khi khởi chạy code chờ một lúc, màn hình game sẽ hiện lên
   
![menu](https://github.com/user-attachments/assets/341599e4-0edd-4054-8b3e-51c59f93d011)

   Người chơi chọn "Play" để bắt đầu trò chơi hoặc "Exit" để thoát khỏi trò chơi.
   
![bat dau choi](https://github.com/user-attachments/assets/1b694631-d21a-4522-9b40-2c235293e1ae)

   Sau khi người chơi chọn "Play", màn chơi sẽ xuất hiện và người chơi cùng trải nghiệm game thôi! 
   
   Người chơi sẽ chiến thắng khi đạt đủ số điểm trong thời gian nhất đinh mà game yêu cầu.
   
![thang](https://github.com/user-attachments/assets/73751a57-f677-4af6-b2cd-1e2acd3e0f5a)

   Người chơi sẽ thua khi không đạt đủ số điểm hoặc hết thời gian.
   
![thua](https://github.com/user-attachments/assets/71b358b5-15e4-4133-a836-f59052b3067b)

3. CÁC THÀNH PHẦN TRONG GAME
   - Jewel: Các viên kim cương với nhiều màu sắc và hình dạng khác nhau, là đơn vị người chơi cần di chuyển các viên kim cương để tạo ra các chuỗi cùng màu, từ đó kiếm điểm.
     ![blue_jewel](https://github.com/user-attachments/assets/aa984435-3903-4f37-bbff-91af790323ae)
     ![green_jewel](https://github.com/user-attachments/assets/f3e301d2-e8c4-41bf-ae60-72e406d40593)
     ![pink_jewel](https://github.com/user-attachments/assets/10f31790-6dbf-449a-b8cd-6781057c2da8)
     ![red_jewel](https://github.com/user-attachments/assets/94789152-65c7-43a5-9440-9e7512f41ae8)
     ![violet_jewel](https://github.com/user-attachments/assets/905fd62a-8d61-4d2b-a1c7-b5eac32db913)
     ![yellow_jewel](https://github.com/user-attachments/assets/11decc23-5964-43eb-80af-5c7ed571501b)
   - Jewel bar: bảng đếm số kim cương mà người chơi đang có và số kim cương người chơi cần thu thập để chiến thắng.
     ![diemkiemduoc](https://github.com/user-attachments/assets/587e6de2-c738-483b-985a-66fadf0814b6)
   - Timer bar: Thời gian còn lại để người chơi hoàn thành.
     ![Screenshot 2024-08-17 230811](https://github.com/user-attachments/assets/8f1b03b1-83c7-4b2c-923a-37cbb0d409fb)
   - Turns remaining circle: Số lượt còn lại của người chơi. Khi người chơi di chuyển kim cương tạo chuỗi cùng màu hay dùng phép bổ trợ sẽ mất đi 1 lượt.
     ![Screenshot 2024-08-17 230838](https://github.com/user-attachments/assets/fbceeef7-1816-4b75-bf4c-6cef5ec6c5b0)
   - Pause button: Người chơi ấn chọn vào để dừng màn chơi lại.
     ![pause_button](https://github.com/user-attachments/assets/453c9ff3-7718-4247-b1b3-24933dc608bd)
   - Ability: các năng lực sẽ được sử dụng trong một điều kiện nhất định.
     + Khi chưa được kích hoạt, các năng lực sẽ trong trạng thái chưa được kích hoạt.
       ![bomb_inactive](https://github.com/user-attachments/assets/a1be122d-dd1f-4ac2-b6c1-bde0d9980fe9)
       ![fist_inactive](https://github.com/user-attachments/assets/88602b87-87b8-4df6-b2a6-9bdcf12f4224)
       ![magnet_inactive](https://github.com/user-attachments/assets/d5848537-94be-4ea0-99e2-1759fa64c755)
     + Magnet: được kích hoạt khi người chơi tạo ra chuỗi 4 kim cương cùng màu, ấn sử dụng và khi người chơi chọn vào một kim cương bất kì sẽ triệt tiêu hàng ngang có chứa viên kim cương đó và cộng điểm cho người chơi.
       ![magnet_active](https://github.com/user-attachments/assets/a6859286-80b9-4919-a85e-feea5c7ce9a6)
     + Fist: được kích hoạt khi người chơi tạo ra chuỗi 5 kim cương cùng màu, ấn sử dụng và khi người chơi chọn vào một kim cương bất kì sẽ triệt tiêu một vùng có chứa viên kim cương đó và cộng điểm cho người chơi.
       ![fist_active](https://github.com/user-attachments/assets/94ed4e8d-8002-4c35-bcb2-5807fa92cb55)
     + Bomb: được kích hoạt khi người chơi tạo ra chuỗi 6 kim cương cùng màu, ấn sử dụng và khi người chơi chọn vào một kim cương bất kì sẽ triệt tiêu một vùng lớn hơn Fist có chứa viên kim cương đó và cộng điểm cho người chơi.
       ![bomb_active](https://github.com/user-attachments/assets/e1d93202-ce22-4af3-bd7f-98c3f91544db)

4. CÁCH CHƠI
   Người chơi ghép các viên kim cương với nhau tạo thành chuỗi để được điểm và cố gắng đạt đến mốc điểm mà game chỉ định trong một khoảng thời gian để dành được chiến thắng.

5. TẢI GAME
   - Cài đặt và setup thư viện đồ họa sfml tại [đây](https://www.sfml-dev.org/).
   - Clone hoặc tải file zip project và thưởng thức thôi!!!
     
6. SOURCE CODE GAME
   - Folder assets: chứa tất cả hình ảnh trong game.
   - Folder include: chứa các khai báo hàm thành phần của game
       + Folder ability: quản lý các năng lực trong trò chơi.
       + Folder Jewels: cung cấp các chức năng cơ bản và thuộc tính chung cho tất cả các loại ngọc trong game.
       + Folder State: Quản lí các trạng thái khác nhau trong trò chơi.
       + Board: đại diện cho bảng chơi trong trò chơi, bao gồm các ô và các viên kim cương. Lớp này cung cấp các chức năng cần thiết để quản lý và thao tác trên bảng, như hoán đổi vị trí của các viên ngọc, xáo trộn bảng, và kiểm tra sự hợp lệ của sự kết hợp các viên ngọc.
       + Button: tạo và quản lý các nút bấm trong trò chơi.
       + Game: quản lý toàn bộ vòng đời của trò chơi, từ khởi tạo đến điều khiển các trạng thái khác nhau của trò chơi.
       + Move: kiểm tra tính hợp lệ của các lượt di chuyển, theo dõi số lượng lượt đi còn lại, và hiển thị thông tin về lượt đi trên màn hình.
       + RandomNumberGenerator: Định nghĩa một hàm để tạo số ngẫu nhiên trong phạm vi cho trước.
       + Score: quản lý và hiển thị điểm số trong trò chơi.
       + Tile: đại diện cho các ô trên bảng trong trò chơi.
       + Timer: quản lý và hiển thị đồng hồ đếm ngược trong trò chơi.
       + configs: Định nghĩa các hằng số và cấu hình cơ bản cho trò chơi, bao gồm cấu hình cửa sổ, trạng thái trò chơi, thư mục tài nguyên, và các thông số trò chơi.
   - Folder src:
       + Ability: quản lý trạng thái và hiển thị của một khả năng (ability) trong trò chơi.
       + BlueJewel, GreenJewel, PinkJewel, RedJewel, VioletJewel, YellowJewel: Nạp texture từ file hình ảnh và gán cho sprite.
       + Board: quản lý bảng trò chơi bằng cách tạo, hiển thị, và xử lý các viên đá quý, kiểm tra và sửa chữa các tổ hợp không hợp lệ, cũng như xử lý các hành động của trò chơi như hoán đổi và xóa viên đá quý.
       + BomBAbility, FistAbility, MagnetAbility: thiết lập các hình ảnh cho khả năng khi nó đang hoạt động và không hoạt động.
       + Button: quản lý các nút trong giao diện người dùng.
       + Game:  quản lý vòng đời và trạng thái của trò chơi.
       + GameState: thiết lập nền cho trạng thái trò chơi.
       + Jewel: quản lý các viên đá quý trong trò chơi.
       + LostState: quản lý trạng thái trò chơi khi người chơi thua cuộc.
       + main: khởi tạo và bắt đầu trò chơi.
       + MainMenuState: quản lý trạng thái menu chính của trò chơi.
       + Move: quản lý và kiểm tra tính hợp lệ của các di chuyển trong trò chơi, đồng thời hiển thị số lượt di chuyển còn lại.
       + PauseState: quản lý giao diện và sự kiện trong trạng thái tạm dừng của trò chơi.
       + PlayState: quản lý logic và giao diện của trạng thái trò chơi chính
       + RandomNumberGenerator: tạo ra một số nguyên ngẫu nhiên.
       + Score: quản lý và hiển thị điểm số trong trò chơi.
       + Tile: quản lý và hiển thị các ô trong trò chơi.
       + Timer: quản lý và hiển thị đồng hồ đếm ngược trong trò chơi.
       + WinState: quản lý trạng thái trò chơi khi người chơi chiến thắng.
    
7. DEMO GAME
   - Link video demo game:
  
8. TÀI LIỆU THAM KHẢO
   - https://www.youtube.com/watch?v=YNXrFOynalE&list=PLB_ibvUSN7mzUffhiay5g5GUHyJRO4DYr&index=10
   - series C++ Sfml 2.0 Made Easy Tutorial: https://www.youtube.com/@CodingMadeEasy
   - https://www.youtube.com/watch?v=TXbRUdZSefw
   - thư viện sfml: https://www.sfml-dev.org/





