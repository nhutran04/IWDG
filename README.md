-Chủ đề: Kiểm tra chức năng IWDG.
-Chức năng: Nút nhất bật tắt đèn, nếu trong 10s không nhấn nút sẽ Reset hệ thống.
-Cách sử dụng: 
1. Mở file cấu hình (.ioc) để xem cấu hình của STM32
2. Gắn dây nạp vào STM32.
3. Mở file project trên STM32CubeIDE để compile và chạy chương trình.
4. Nhấn nút User để hệ thống bắt đầu hoạt động ( 2 đèn sáng: 1 đèn chức năng (bật/tắt), 1 đèn trạng thái )
   - Nếu đèn đang ở trạng thái sáng , sau 10s không nhấn nút thì reset 2 đèn tắt.
   - Nếu đèn đang ở trạng thái tắt, sau 10s không nhấn nút reset đèn trạng thái. 
