**Tìm hiểu về Ubuntu và một số câu lệnh hay dùng**

##Mục lục

* [1. Tìm hiểu Ubuntu LTS là gi?](#1)
    * [1.1 Tìm hiểu về thông số phiên bản Ubuntu](#1.1)
* [2. Tìm hiểu về cấu trúc thư mục trong Ubuntu](#2)
    * [2.1 /Root](#2.1)
    * [2.2 /bin](#2.2)
    * [2.3 /etc](#2.3)
    * [2.4 /dev](#2.4)
    * [2.5 /proc](#2.5)
* [3. Một số lệnh command hay dùng](#3)
    * [3.1 Lệnh về trình báo màn hình](#3.1)
    * [3.2 Lệnh về thư mục](#3.2)
    * [3.3 Lệnh về tập tin](#3.3)
    * [3.4 Lệnh về quản lý tiến trình](#3.4)


<a name="1"></a>
**1. Tìm hiểu về Ubuntu LTS là gì?**

**LTS** là viết tắt của **Long Term Support** có nghĩa là *hỗ trợ dài hạn*.Trong thời gian hỗ trợ, các kĩ sư luôn luôn cập nhật các bản sửa lồi để nâng cao trải nghiệm người dùng cũng như **hiệu suất hệ thống**. Chính vì vậy bạn nên cập nhật các thông tin nhanh và chính xác để có thể đáp ứng tốt nhất cho công việc của bạn.

Cứ sau 2 năm thì mọt phiên bản **LTS** được phát hành. Trong các bản **LTS** trước đó thì thời gian hỗ trợ là 3 năm đối với bản **Desktop** và 5 năm đối với bản dành cho **Server**. Bắt đầu từ bản **12.04** thì đều hỗ trợ là 5 năm đối với cả hai phiên bản.


<a name="1.1"></a>
Ví dụ về bản Ubuntu 12.04. Có nghĩa là phiên bản này được phát hành vào tháng 4 năm 2012. Tương tự với bản **16.04** thì nó được phát hành vào tháng 4 năm 2016. Phiên bản này được đánh giá là ổn định và đáng trải nghiệm nhất trong các phiên bản hiện tại của Ubuntu. hiện nay, phiên bản mới nhất là 17.10 và sắp tới là **18.04**.



<a name="2"></a>
**2. Tìm hiểu vầ cấu trúc thư mục trong Ubuntu**

Các chương trình trong **Ubuntu** được lưa dưới dạng nhiều thư mục khác nhau như **/bin**, **/etc**, **/var**,...
Tôi và các bạn sẽ tìm hiểu lần lượt về từng thư mục và ý nghĩa của chúng.

<img src="https://i.imgur.com/Te1HvZS.png">

<a name="2.1"></a>
**2.1 /Root**

Là nới bắt đầu của tất cả các file cà thư mục. Chỉ có **root user** mới có quyền ghi trong thư mục này.


<a name="2.2"></a>
**2.2 /bin** 
Đây là thư mục chứa **chương trình của người dùng.
Thư mục này chứa các chương trình thực thi của người dùng.
Ví dụ: **ps**, **top**, **ls**.... 
Phần này sẽ được chúng ta tìm hiểu vào phần sau.

<a name="2.3"></a>
**2.3 /etc**

Đây là thư mục chứa tất cả các file **cấu hình** mà chúng ta đã cài đặt. Ngoài ra thư mục này còn chưa các **shell script** dùng để khởi động chương tình hoặc tắt một chương trình nào đó.

<a name="2.4"></a>
**2.4 /dev**

thư mục này chứa thông tin về các **thiết bị** kết nối với máy của bạn.
Ví dụ như ổ cứng, các thiết bị ngoại vi như USB, ổ cứng đều được lưu trữ tại đây.
Ví dụ: **/dev/sdb1** là tên của **USB** bạn vừa cắm vào máy.


<a name="2.5"></a>
**2.5 /proc**

Thông tin về các tiến trình đang chạy sẽ được lưu trong /proc dưới dạng một hệ thống file thư mục mô phỏng.
Ví dụ: thư mục con **/proc/{pid}** chứa các thông tin về tiến trình có **ID** là **pid (pid ~ process ID). 


<a name="3"></a>
**3. Một số lệnh command hay dùng**

Trong quá trình sử dụng linux, bạn phải làm quen rất nhiều câu lệnh command để có thể phục vụ cho công việc của bạn.


<a name="3.1"></a>
**3.1 Lệnh về trình báo màn hình**

   * **echo**: hiển thị dòng kí tự và biến.
   * **cal**: máy tính cá nhân.
   * **date**: hiển thị thời gian.
   * **vi**: trình soạn thảo văn bản
Cách dùng các câu lệnh trên bạn có thể tham giảo **GG** để biết rõ thêm :))


<a name="3.2"></a>
**3.2 Lệnh về thư mục**

**cd**: chuyển đổi thư mục.
**cp**: copy thư mục hoặc file.
**mkdir**: tạo thư mục.
**rm**: loại bỏ thư mục.


<a name="3.2"></a>
**3.3 Lệnh về tập tin**

**find**: tìm vị trí tập tin
**grep**: tìm vị trí của chuối kí tự trong tập tin.
**ls**: liệt kê các file và thư mục
**cat**: hiển thị nội dung một tập tin.



<a name="3.4"></a>
**3.4 Lệnh về quản lý tiến trình**

**kill**: để tắt đi một tiến trình.
**ps**: hiển thị trạng thái tiến trình.



