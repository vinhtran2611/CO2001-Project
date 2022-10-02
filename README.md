# CO2001-Project

## Bài 1: Vẽ ống
Ở bài 1, Mình sẽ vẽ các ống màu xanh và làm nó di chuyển.

Mục tiêu:
- Các ống màu xanh luôn di chuyển qua trái 
- Ống nào đi hết qua trái rồi phải có ống mới được tạo ra
- Các ống có chiều cao ngẫu nhiên
- Luôn có 2 ống đối diện nhau
- Khoảng cách giữa ống trên và ống dưới không đổi


## Bài 2: Vẽ chim
Ở bài 2, mình cần vẽ được con chim. <br>

Đây thực chất là 1 ô vuông, nó di chuyển lên xuống, vì ống luôn đi sang trái nên có cảm giác như con chim đang di chuyển. Thực chất là con chim chỉ đứng im và biết nhảy và rơi.<br>
Mục tiêu:
- Bấm phím cách (space) để làm con chim nhảy lên 
- Làm chim rơi tự do (tốc độ rơi tăng dần theo thời gian)

## Bài 3: Tính điểm
Ở bài 3, mình sẽ tính điểm, khi chim đi qua 1 ống thì điểm được +1.<br>
Nghe có vẻ đơn giản, tuy nhiên, bạn không thể chỉ xét xem khi nào ống ở bên trái con chim. Nếu làm vậy thì điểm cứ tăng liên tục khi chim đi qua ống.<br>
Mình cần xét xem khi nào chim đi qua ống rồi, và quan trọng là, nếu đã đi qua rồi thì đánh dấu là đi qua rồi và không tính điểm cho ống đó nữa.

## Bài 4: Dừng màn hình khi chết
Ở bài 4:
- Màn hình sẽ dừng lại khi chim chết (chạm vào ống hoặc rơi)
- Khi chết sẽ hiện điểm, chữ "Game Over" 
- Người chơi có thể bấm dấu cách (Space) để chơi lại. <br>

Cái số 3 cần tinh tế một tí vì nút Space vừa dùng để nhảy vừa dùng để chơi lại khi đã chết

## Bài 5: Dùng hình thật
Ở bài 5, mình sẽ thay hình nền và hình còn chim.<br>

Cực kì đơn giản, mình cần download ảnh trên mạng (bạn search google chữ flappy bird assets), từ assets nghĩa là các thứ mà game đó sử dụng, như là âm thành, hình vẽ, mầu sắc, font chũ.<br>

Đối với ảnh, nó được hiểu như 1 hình chữ nhật mà thôi, mình sẽ load ảnh bằng đường dẫn, sau đó chỉnh kích thước ảnh nếu cần và thay hình mình vẽ bằng ảnh.<br>

Mình để ảnh mình dùng ở đây, bạn có thể download và dùng, ảnh chim mình không up được đúng định dạng qua facebook, bạn nên tải 1 ảnh transparent (ảnh trong suốt) trên mạng. Nhìn sẽ đẹp hơn, không có viền nền.<br>

