# CÁC CHẾ ĐỘ KẾT NỐI MẠNG TRÊN VMWARE

- Có ba chế độ kết nối mạng trên VMWARE:
  <ul>
  <li> Chế độ Bridge</li>
  <li> Chế độ Host-only</li>
  <li> Chế độ NAT( Network Address Translation )</li>
  </ul>

## Chế độ Bridge

  <img src="/images/Bridge.png" />

- Ở chế độ này, card mạng trên máy ảo được gán vào VMnet0. VMner0 liên kết trực tiếp với card mạng vật lý trên máy thật. Khi đó, máy ảo sẽ kết nối Internet qua card mạng vật lý và có chung lớp mạng với card mạng vật lý.

- Card Bridge trên máy ảo chỉ có thể giao tiếp với card mạng thật trên máy thật và có thể giao tiếp với mạng mà máy tính vật lý đang kết nối.

## Chế độ Host-only

   <img src="/images/Host-only.png" />

- Máy ảo được kết nối với VMnet ở chế độ Host-only. Card Host-ony được kết nối với một card mạng ảo tương ứng trên máy thật ( trong trường hợp này là VMnet1) và chỉ có thể giao tiếp được với card mạng ảo này. Card Host-only có thể giao tiếp với các card Host-only trên các máy ảo khác.

- IP của máy ảo được cấp bởi DHCP server
của VMnet tương ứng.

- Ở chế độ này, các máy ảo không có kết nối vào mạng vật lý bên ngoài thông qua máy thật, có nghĩa là mạng VMnet Host-only nằm hoàn toàn trong máy chủ và hoàn toàn tách biệt với mạng vật lý của máy chủ.

## Chế độ NAT
 
   <img src="/images/NAT.png" />

- Ở chế độ NAT, card mạng của máy ảo được kết nối với VMnet8. VMnet8 cho phép máy ảo đi ra mạng vật lý bên ngoài Internet thông qua cơ chế NAT. Lớp mạng bên trong máy ảo khác hoàn toàn với lớp mạng của card vật lý bên ngoài, hai mạng hoàn toàn tách biệt với nhau. 

- IP của card mạng máy ảo sẽ được cấp bởi DHCP server của VMnet8. 

- Card NAT không thể giao tiếp với mạng vật lý mà máy thật đang kết nối. Tuy nhiên, cơ chế NAT cho phép dịch địa chỉ IP của máy ảo ra địa chỉ IP của máy thật để máy ảo có thể liên lạc với mạng vật lý bên ngoài.
   