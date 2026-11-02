# th-th-nh-1-
chill chill
🌌 Bầu Trời Sao 3D - Lời Tỏ Tình Của Dân IT
Dự án này là một trang web tĩnh (Static Web) tạo hiệu ứng 3D dải ngân hà xoay quanh một hành tinh phát sáng bằng HTML5 Canvas và JavaScript thuần. Nó đi kèm với một câu quote lãng mạn, rất thích hợp để làm một món quà bất ngờ hoặc video "thả thính".

📁 Cấu trúc thư mục
Bạn chỉ cần một file duy nhất để chạy toàn bộ dự án:

index.html: Chứa toàn bộ giao diện (HTML), kiểu dáng (CSS) và logic xử lý đồ họa (JavaScript).

🚀 Hướng dẫn sử dụng
1. Chạy trên máy tính (Desktop)
Rất đơn giản, bạn chỉ cần mở thư mục chứa code và nháy đúp chuột vào file index.html. Trình duyệt mặc định (Chrome, Edge, Safari...) sẽ tự động mở lên và chạy hiệu ứng.

2. Chạy trên điện thoại (Mobile)
Trình duyệt trên điện thoại không cho phép mở file HTML trực tiếp từ bộ nhớ máy. Để xem trên điện thoại, bạn cần thiết lập một Local Server (Máy chủ cục bộ):

Sử dụng Visual Studio Code (Khuyên dùng):

Mở thư mục chứa file index.html bằng VS Code.

Cài đặt tiện ích (extension) Live Server.

Nhấp chuột phải vào file index.html và chọn Open with Live Server.

Đảm bảo máy tính và điện thoại kết nối chung một mạng Wi-Fi.

Mở Command Prompt (cmd) trên máy tính, gõ ipconfig để lấy địa chỉ IPv4 (VD: 192.168.1.10).

Mở trình duyệt trên điện thoại, gõ địa chỉ IPv4 kèm theo cổng (Port) của Live Server. VD: http://192.168.1.10:5500.

🛠️ Hướng dẫn tùy chỉnh (Customization)
Bạn có thể mở file index.html bằng bất kỳ trình soạn thảo code nào (Notepad, VS Code) để thay đổi các thông số sau:

Thay đổi lời tỏ tình: Tìm đến dòng chữ <div class="overlay">...</div> (Khoảng dòng 40) và sửa lại nội dung trong thẻ <h1> và <p> theo ý muốn.

Tăng giảm số lượng sao: Tìm biến const numParticles = 3000; trong thẻ <script> (Khoảng dòng 59). Giảm số này xuống nếu điện thoại của bạn bị giật/lag.

Tốc độ xoay: Tìm dòng angleY -= 0.005; (Khoảng dòng 102). Tăng giá trị 0.005 lên nếu bạn muốn dải ngân hà quay nhanh hơn.

Màu sắc hành tinh: Tìm hàm drawPlanet() và thay đổi các mã màu hex (như #00aaff, #0022aa) thành mã màu bạn thích (VD: #ff00aa cho màu hồng).

📄 Giấy phép (License)
Dự án này là mã nguồn mở, bạn có thể tự do sử dụng, chỉnh sửa và chia sẻ.
