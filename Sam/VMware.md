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
<<<<<<< HEAD

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

   <img src="http://2.pik.vn/2018a4eee906-97d2-4152-8ca2-7c1d04808752.png">

   <li> VMWare sẽ tối ưu giúp bạn toàn bộ các bước cài đặt.</li> 

   <img src="http://2.pik.vn/2018d675b966-16eb-48b0-a78d-6a217522ccf5.png">

   <li> Sau khi cài xong bạn có thể đăng nhập vào và sử dụng.</li>

   <img src="http://2.pik.vn/201836627746-01fe-451a-a7eb-5bd0af4cd1d2.png">

   <li> Giao diện Ubuntu có đôi chút khác biệt so với Windows.</li>

   <img src="http://2.pik.vn/2018a801b5d6-0ddf-443a-93fc-b650f7f62aea.png">

=======
   
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
   
>>>>>>> f14d16ef19e0ac6cd3b7448ad5a6ac5b11509b7f
   <li> Như vậy là chúng ta đã hoàn tất việc cài Ubuntu trong VMWare.</li>
   </ul>

## 2. Thêm card mạng cho máy ảo
- *Khái niệm VMnet*: các card mạng ảo trong VMware sẽ được gọi là VMnet.
- Khi mới cài đặt VMware Workstation, mặc định phần mềm sẽ cài cho chúng ta 2 card mạng như hình dưới. Đó là VMware Network Adapter VMnet1 và VMware Network Adapter VMnet8. Tương đương với việc từ máy thật hiện tại đã được cắm dây mạng với 2 Switch ảo VMnet1 và VMnet8. Do đó chỉ cần đặt địa chỉ IP cho 2 card mạng này của máy thật cùng dải IP với các máy ảo cũng nối vào 2 Switch ảo này, thì máy thật và máy ảo có thể kết nối với nhau qua một trong 2 card mạng này.

  <img src="http://2.pik.vn/20181616d133-d357-46fd-950e-1dbbccded193.png">

  - Để xem các card mạng đã có trong VMware Workstation ta chỉ cần bật VMware lên, chọn *Edit* => *Virtual Network Editor*.

      <img src="http://2.pik.vn/20188c5aa962-2964-4c35-937b-d67dde863139.png">
     <ul>
     <li> Hình trên là máy tính có 3 card mạng, trong đó card thứ nhất được gán vào Vmnet0 (chế độ Bridge), còn card thứ 2 được gán vào Vmnet1 (chế độ Host-Only), card thứ ba được gán vào Vmnet8 (chế độ NAT). Có thể thấy với mỗi card mạng của máy ảo, nó có thể được gán vào một trong 20 Vmnet từ Vmnet0 đến Vmnet19. Mỗi Vmnet chính là 1 bộ chia mạng ảo hay Switch ảo mà Vmware Workstation tạo ra.</li>
     <li> Bridge: Card này sử dụng card vật lý (LAN, Wifi, Bluetooth…) của máy thật để chia sẻ kết nối. Mặc định VMware để Bridge ở chế độ Automatic, tức là VMware sẽ tự động chọn một trong những card mạng vật lý của máy thật để chia sẻ kết nối.</li>

     <img src="http://2.pik.vn/201821c4cb08-a1a0-4383-acb5-a0dbeb10154e.png">

      <li> Host-Only: Ở chế độ này Switch ảo không được kết nối gì với các card vật lý của máy tính thật. Các máy tính ở chế độ Host-Only có cùng dải IP sẽ kết nối được với nhau nhưng không thể kết nối ra các thiết bị vật lý khác bên ngoài bởi nó không có liên quan gì đến card vật lý của máy thật. Vmware có lựa chọn cho phép Vmware là 1 thiết bị cấp phát DHCP cho các thiết bị kết nối vào Switch ảo. Nếu chọn chức năng này, các thiết bị nối đến Switch ảo này sẽ nhận được địa chỉ do chính VMware cấp. Chúng ta có thể thay đổi dải địa chỉ này theo ý muốn trong mục DHCP Settings. </li>

     <img src="http://2.pik.vn/2018aeff944b-e8e2-4ced-a9ee-24f6c93ee9f3.png">

     <img src="http://2.pik.vn/2018f6103175-8341-4a82-9d0e-bfed905e11ab.png">

     <li> NAT: card này sẽ Nat địa chỉ IP của máy thật ra một địa chỉ khác cho máy ảo sử dụng. Card này cũng có thể kết nối ra bên ngoài Internet.</li>
     </ul>

### 2.1. Thêm, xóa một vmnet
- **Thêm một VMnet**: Cũng trong *Virtual Network Editor* ta chọn như sau:

  <img src="http://2.pik.vn/201881e1edf8-3bef-4d08-a975-a7cd4df1f342.png">
  
   <ul>
   <li> Chọn VMnet cần thêm sau đó chọn chế độ cho VMnet đó, dược kết quả như sau:</li>
   <img src="http://2.pik.vn/201893c45ba3-43aa-406e-a5a7-3ad48898bd98.png">
   <li> Trong hình trên, mình thêm 1 VMnet2 sử dụng chế độ Host-Only, VMnet này được gắn tự động một dải IP.</li>
   </ul>

- **Xóa một VMnet**: trong *Virtual Network Editor* chọn một vmnet và ấn *Remove Network* (button cạnh Add Network)

  <img src="http://2.pik.vn/201834e08eb4-e589-4b7c-9732-ec48c7b8e5c8.png">

- **Lưu ý**: 

   <ul>
   <li> Tại 1 thời điểm, chỉ 1 VMnet được đặt ở chế độ NAT.</li>
   <li> Tại 1 thời điểm chỉ 1 card vật lý của máy thật được Bridge vào 1 VMnet (Switch ảo).</li>
   <li> Chế độ Host-Only thì thoải mái, mỗi một VMnet các bạn có thể để nó ở chế độ Host-Only, tuy nhiên các VMnet cùng để ở chế độ Host-Only không thông nhau (chúng là các Switch riêng rẽ không được nối với nhau).</li>
   </ul>

- **Sửa dải IP một VMnet**: Trong dòng Subnet IP chọn dải IP và subnet muốn thay đổi.

  <img src="http://2.pik.vn/20186778d4e4-402b-4843-9152-8782eb499923.png">

  Click *Apply* sau đó ấn *OK*.

- **Thêm một card mạng vào máy ảo**: 
  <ul>
  <li> Thực hiện trên máy ảo Ubuntu Desktop 16.04 gắn sẵn một card bridge khi tạo máy ảo.</li>
  <li> Show IP trên máy ảo bằng lệnh *ifconfig* trong *Terminal*.</li>

  <img src="http://2.pik.vn/20189e7a5163-5e54-4051-9cbb-6eaead3c121d.png">

  <li> Thêm card mạng thứ 2 vào máy ảo bằng cách vào Edit Virtual Machine Settings, chọn *Add* => *Network* và làm theo hướng dẫn trong hình sau:</li>

  <img src="http://2.pik.vn/2018c7ce61ba-da5e-4d6d-8473-d5b0a7f6d85f.png">

  <img src="http://2.pik.vn/201881e76a27-0432-4b61-be7f-75d383afbb78.png">

  <li> Xin cấp IP cho card mạng mới trên máy ảo bằng lệnh *dhclient eth1*.</li>
  

  










       

























