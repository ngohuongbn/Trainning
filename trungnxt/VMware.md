# **3 CHẾ ĐỘ MẠNG TRONG VMWARE WORKSTATION 12**

# Mục lục
* [1.NAT-Network Address Translation](#1)
* [2.Bridged Networking](#2)
* [3.Host-Only Networking](#3)
=======================================================================

<a name="1"></a>
# 1. NAT-Network Address Translation

<img src="https://github.com/Tuantrung/FIL-Tuantrung/blob/master/New%20folder/Screenshot_1.png">


- NAT cung cấp một truy cập máy ảo tới các tài nguyên mạng sử dụng địa chỉ IP của máy chủ lưu trữ.

- Kết nối dịch vụ địa chỉ mạng được thiết lập tự động nếu bạn theo đường dẫn **Custom** trong "**New Virtual Machine Wizard**" và chọn  **Use network address translation**

- Nếu bạn muốn kết nối với Internet hoặc các mạng TCP / IP khác sử dụng mạng quay số (**dial-up networking**) hoặc kết nối băng thông rộng(**boardband connection**) của máy chủ và bạn không thể cung cấp cho máy ảo một địa chỉ IP trên mạng bên ngoài, NAT thường là cách dễ nhất để cung cấp cho máy ảo của bạn truy cập vào mạng đó. 

- NAT cũng cho phép bạn kết nối với một mạng TCP / IP sử dụng bộ chuyển đổi Token Ring trên máy chủ

- Nếu bạn sử dụng NAT, máy ảo của bạn sẽ không có địa chỉ IP riêng trên mạng bên ngoài. Thay vào đó, một mạng riêng tư riêng được thiết lập trên máy chủ. Máy ảo của bạn nhận được một địa chỉ trên mạng đó từ máy chủ DHCP ảo VMware. Thiết bị NAT VMware truyền dữ liệu mạng giữa một hoặc nhiều máy ảo và mạng bên ngoài. Nó xác định các gói tin dữ liệu đến cho mỗi máy ảo và gửi chúng đến đúng đích.

- Nếu bạn chọn NAT, máy ảo có thể sử dụng nhiều giao thức TCP / IP tiêu chuẩn để kết nối với các máy khác trên mạng bên ngoài. Ví dụ, bạn có thể sử dụng HTTP để duyệt các trang web, FTP để chuyển các tập tin và Telnet để đăng nhập vào các máy tính khác. Trong cấu hình mặc định, máy tính trên mạng bên ngoài không thể bắt đầu kết nối với máy ảo. Điều đó có nghĩa là, ví dụ, cấu hình mặc định không cho phép bạn sử dụng máy ảo như một máy chủ Web để gửi các trang web tới các máy tính trong mạng bên ngoài.

- Nếu bạn thực hiện một số lựa chọn khác trong New Virtual Machine Wizard và sau đó quyết định sử dụng NAT, bạn có thể thực hiện thay đổi đó trong trình biên tập cài đặt máy ảo (**VM** > **Settings**).

<a name="2"></a>
## 2. Bridged Networking

<img src="https://github.com/Tuantrung/FIL-Tuantrung/blob/master/New%20folder/Screenshot_2.png">

- **Bridged networking** kết nối một máy ảo với mạng sử dụng bộ điều hợp Ethernet của máy chủ lưu trữ
- Kết nối mạng được thiết lập tự động nếu bạn chọn **Use bridged networking** trong **New Virtual Machine Wizard** hoặc nếu bạn chọn **typical**. Lựa chọn này chỉ có trên máy chủ Linux nếu bạn cho phép tùy chọn cầu nối mạng khi cài đặt VMware Workstation.
- Nếu máy chủ của bạn đang ở trong một mạng Ethernet, đây thường là cách đơn giản nhất để cho phép máy ảo của bạn truy cập vào mạng đó. Máy chủ Linux và Windows có thể sử dụng **Bridge** để kết nối với mạng có dây. Ngoài ra, cầu nối mạng không dây được hỗ trợ cho máy chủ Windows.
- Nếu bạn sử dụng **Bridge**, máy ảo của bạn cần có danh tính riêng trên mạng. Ví dụ, trên một mạng TCP / IP, máy ảo cần địa chỉ IP riêng của nó. Quản trị viên mạng của bạn có thể cho bạn biết địa chỉ IP có sẵn cho máy ảo của bạn và cài đặt mạng nào bạn nên đsử dụng trong hệ iều hành khách. Nói chung, hệ điều hành 'khách' của bạn có thể tự động nhận địa chỉ IP và các chi tiết mạng khác từ máy phục vụ DHCP hoặc bạn có thể cần cài đặt địa chỉ IP và các chi tiết khác theo cách thủ công trong hệ điều hành 'khách'.
- Nếu bạn sử dụng **Bridge**, máy ảo là một người tham gia đầy đủ trong mạng. Nó có quyền truy cập vào các máy khác trên mạng và có thể được liên lạc bởi các máy khác trên mạng như thể nó là một máy tính vật lý trên mạng.
- Lưu ý rằng nếu máy chủ được thiết lập để khởi động nhiều hệ điều hành và chạy một hoặc nhiều máy ảo trong máy ảo, bạn cần phải cấu hình từng hệ điều hành với một địa chỉ mạng duy nhất. Những người khởi động nhiều hệ điều hành thường chỉ định tất cả các hệ thống cùng một địa chỉ, bởi vì họ cho rằng chỉ có một hệ điều hành sẽ chạy cùng một lúc. Nếu bạn sử dụng một hoặc nhiều hệ điều hành trong một máy ảo, giả thiết này không còn đúng nữa.
- Nếu bạn thực hiện một số lựa chọn khác trong **New Virtual Machine Wizard** và sau đó quyết định sử dụng **Bridge**, bạn có thể thực hiện thay đổi đó trong trình biên tập cài đặt máy ảo (**VM** > **Settings**).

<a name="3"></a>
# 3. Host-Only Networking
<img src="https://github.com/Tuantrung/FIL-Tuantrung/blob/master/New%20folder/Screenshot_3.png">

- **Host-only networking** tạo ra một mạng hoàn toàn nằm trong máy chủ
- **Host-only networking** chỉ được thiết lập tự động nếu bạn chọn **Use Host-only Networking** trong **New Virtual Machine Wizard**. Trên máy chủ Linux, lựa chọn này chỉ khả dụng nếu bạn kích hoạt tùy chọn mạng máy chủ lưu trữ chỉ khi bạn cài đặt **VMware Workstation**.
- **Host-only networking** chỉ cung cấp kết nối mạng giữa máy ảo và máy chủ, sử dụng một bộ điều hợp Ethernet ảo hiển thị cho hệ điều hành máy chủ lưu trữ. Cách tiếp cận này có thể hữu ích nếu bạn cần thiết lập một mạng ảo bị cô lập.
- **Routing and Connection sharing**
<ul>
<il> Nếu bạn cài đặt đúng phần mềm định tuyến hoặc proxy trên máy chủ của mình, bạn có thể thiết lập kết nối giữa bộ điều hợp Ethernet máy chủ ảo và một bộ điều hợp mạng vật lý trên máy chủ. Điều này cho phép bạn, ví dụ, để kết nối máy ảo với một Token Ring hoặc mạng không phải là Ethernet.</il>
</ul>

