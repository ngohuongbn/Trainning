# I. Khái niệm VMware Workstation
- VMware là phần mềm tạo máy ảo với hiệu năng hoạt động mạnh mẽ cho phép chạy song song nhiều hệ điều hành cùng lúc, rất hữu ích khi bạn chơi game hoặc thử nghiệm các phần mềm. 
- Nếu bạn muốn vọc các hệ điều hành, phần mềm và các ứng dụng khác, bạn sẽ cần dùng máy ảo. Nó không chỉ cho phép bạn thực hiện các hành động không thể thực hiện trên máy thật, mà còn bảo vệ bạn khỏi virut hay sai lầm bạn có thể gây ra.
- VMware là cách đơn giản nhất để bạn tạo máy ảo và chạy song song nhiều hệ điều hành trên cùng một máy tính, rất hữu ích khi người dùng muốn thử nghiệm một hệ điều hành mới, kiểm tra tính tương thích với hệ thống. VMware hỗ trợ những phần cứng mới nhất, cải thiện khả năng kết nối, hiển thị màn hình với độ phân giải cao và có thể chia sẻ dữ liệu trong môi trường an toàn.
- VMware Workstation thực hiện sao chép môi trường máy chủ, desktop, máy tính bảng trong máy ảo, có khả năng chạy các ứng dụng yêu cầu cao trong môi trường ảo, có thể truy cập máy ảo dễ dàng qua môi trường đám mây.
- Với phần mềm này, người dùng dễ dàng và nhanh chóng có thêm nhiều máy tính ảo để sử dụng hay làm các bài Lab từ một chiếc máy tính thật của mình. Những máy tính ảo này không khác gì so với máy tính thật và nó sử dụng tài nguyên (CPU, RAM, HDD) từ tài nguyên của máy tính vật lý thật. Do đó việc tạo ra được số lượng máy tính hay mức độ cấu hình của máy tính ảo phải tính toán sao cho phù hợp với tài nguyên của máy vật lý thật.
- *Một số tính năng chính của VMware Workstation*:
   <ul>
   <li> Cài đặt nhiều hệ điều hành khác nhau trên cùng một hệ điều hành.</li>
   <li> Cho phép quản trị hệ thống và kiểm tra các phần mềm bao gồm các ứng dụng mới, cập nhật ứng dụng...</li>
   <li> Giới thiệu cơ sở hạ tầng ảo cho các doanh nghiệp.</li>
   <li> Máy ảo được tạo ra trong Workstation có thể triển khai các nền tảng ảo hóa.</li>
   </ul>

- Có thể download và cài đặt VMware Workstation một cách dễ dàng tại [link](https://my.vmware.com/web/vmware/info/slug/desktop_end_user_computing/vmware_workstation/10_0)
- Trong bài này, phiên bản VMware tôi sử dụng là VMware Workstation 12 Pro.
- Sau khi cài đặt xong, giao diện của VMware sẽ như sau:

   <img src="http://2.pik.vn/201881a89485-e88a-4652-809f-d037d1e54826.png">

# II. Các thao tác với VMware

## 1. Tạo một máy ảo trên VMware
- Ubuntu là một hệ điều hành máy tính dựa trên Debian GNU/Linux, một bản phân phối Linux thông dụng. Ubuntu là phần mềm mã nguồn mở tự do, có nghĩa là người dùng được tự do chạy, sao chép, phân phối, nghiên cứu, thay đổi và cải tiến phần mềm theo điều khoản của giấy phép GNU GPL.
- Sau đây, tôi sẽ hướng dẫn cho các bạn cách cài đặt hệ điều hành Ubuntu Desktop 16.04 trên máy ảo VMware.
- Chú ý:
   <ul>
   <li> Phiên bản VMware tôi sử dụng là VMware Workstation 12 Pro.</li>
   <li> Host cài đặt VMware: Windons 10 Pro.</li>
   <li> Phiên bản Ubuntu cài đặt là Ubuntu Desktop 16.04</li>
   </ul>

- Nếu bạn chưa có file Ubuntu, vào trang web [này](https://www.ubuntu.com/download) để tải về miễn phí file *iso*.
- Sau đây là các bước cài đặt Ubuntu:
   <ul>
   <li> Bước 1: mở VMware, lựa chọn *Create a New Virtual Machine*.</li>
   
   <img src="http://2.pik.vn/2018ee6a34d0-4536-4a73-ab45-61061e1baa71.png">
   
   <li> Bước 2: Để mặc định là *Typical* rồi nhấn *Next*.</li>
   
   <img src="http://2.pik.vn/2018caacad41-1248-43c0-8491-35836a28d2ee.png">
   
   <li> Bước 3: Lựa chọn *Installer disc image file* rồi *Browse* để tìm đường đẫn đến nơi chứ file Ubuntu iso của bạn.</li>
   
   <img src="http://2.pik.vn/20189387c522-3bda-4b25-889a-8d6c89cd1af1.png">
   
   <li> Bước 4: Lựa chọn file iso UBuntu bạn tải về khi nãy rồi *Open*.</li>
   
   <img src="http://2.pik.vn/2018213412ad-0b60-41ed-9f7f-962d2edafe07.png">
   
   <li> Bước 4: Quay trở lại giao diện chọn file, lúc này bạn chỉ cần ấn *Next* để sang bước tiếp theo.</li>
   
   <img src="http://2.pik.vn/201892b0aec2-aa20-447b-987f-6e21c8ff906e.png">
   
   <li> Bước 5: Điền tên tài khoản, user cũng như mật khẩu cho Ubuntu khi bạn đăng nhập vào rồi tiếp tục bấm *Next*.</li>
   
   <img src="http://2.pik.vn/201873cc135f-e465-48ad-8e7b-654ac774c283.png">
   
   <li> Bước 6: Lựa chọn tiếp tên hiển thị máy và nơi chưa dữ liệu cho VMWare Ubuntu.</li>
   
   <img src="http://2.pik.vn/20182566f686-b985-46fb-8074-f17abe6a7087.png">
   
   <li> Bước 7: Lựa chọn dung lượng tối đa mà Ubuntu được cho, bạn có thể thay đổi nếu ổ cứng bạn trống nhiều, còn không cứ tiếp tục *Next*.</li> 
   
   <img src="http://2.pik.vn/201877d404bf-051c-417f-a146-0e5729f09209.png">
   
   <li> Bước 8: Đây là bước tùy chỉnh cấu hình, thông thường bạn nên nâng cao RAM lên một chút dể sử dụng đỡ bị giật hoặc lag. Tuy nhiên cần chú ý việc này ảnh hưởng tới máy chính của bạn. Ngoài RAM có thể chỉnh tối đa lên 64 GB bạn còn có thể tùy chỉnh nhiều thứ khác nữa như CPU hay kết nối DVD, mạng, USB.</li>
   
   <img src="http://2.pik.vn/201821297114-8ad2-4d9e-9304-e19ccea55c9c.png">

   <img src="http://2.pik.vn/2018e289670a-f661-415a-bc96-92a68ecf53d4.png">
   
   <li> Bước 9: Đến bước này bạn chỉ việc ngồi chờ hệ thống cài Ubuntu trong VMWare mà thôi.</li>
   
   <img src="http://2.pik.vn/201848d98cbf-497a-40d8-84ae-c153b3522b96.png">
   
   <li> VMWare sẽ tối ưu giúp bạn toàn bộ các bước cài đặt.</li> 
   
   <img src="http://2.pik.vn/2018147d8eb7-5d46-4dd9-a6a7-2fce8f134ee3.png">
   
   <li> Sau khi cài xong bạn có thể đăng nhập vào và sử dụng.</li>
   
   <img src="http://2.pik.vn/20184c38dc66-8259-4e16-8aa2-2d1c030d8190.png">
   
   <li> Giao diện Ubuntu có đôi chút khác biệt so với Windows.</li>
   
   <img src="http://2.pik.vn/2018a801b5d6-0ddf-443a-93fc-b650f7f62aea.png">
   
   <li> Như vậy là chúng ta đã hoàn tất việc cài Ubuntu trong VMWare.</li>
   </ul>

## 2. Thêm card mạng cho máy ảo
- *Khái niệm VMnet*: các card mạng ảo trong VMware sẽ được gọi là VMnet.
- Khi mới cài đặt VMware Workstation, mặc định phần mềm sẽ cài cho chúng ta 2 card mạng như hình dưới.

  <img src="http://2.pik.vn/20181616d133-d357-46fd-950e-1dbbccded193.png">

  - Để xem các card mạng đã có trong VMware Workstation ta chỉ cần bật VMware lên, chọn *Edit* => *Virtual Network Editor*.

  <img src="http://2.pik.vn/2018baf38095-1fc0-41ab-88cb-7643bf4790b7.png">

### 2.1. Thêm, xóa một vmnet













