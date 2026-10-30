

# Mạng là gì

- Mạng máy tính là mạng lưới viễn thông số cho phép các node chia sẻ tài nguyên


# Xây 1 mạng

- Cho 2 máy tính kết nối với nhau bằng 1 cable thì ta sẽ được 1 mạng.
- Ngoài đời cũng vậy 1 mạng sẽ được tạo ra bởi các máy tính kết nối với nhau thông qua băng thông.



# Client (Máy khách)

- Là 1 thiết bị trong mạng sử dụng các dịch vụ được cung cấp bởi server

# Servers (Máy chủ)

- Ngược lại với máy khách ta có định nghĩa:
- Server là 1 thiết bị cung cấp tính năng hoặc dịch vụ cho clients


# Server and Client

- Vai trò giữa server và client có thể thay đổi lẫn nhau trong 1 mô hình

- Ví dụ: youtube server sẽ trả về dịch vụ stream video mong muốn lên máy chúng ta => chúng ta xem được video


# Switch
![[Pasted image 20261031030831.png]]

- Là 1 thiết bị:
	- có nhiều network interfaces/ports để các end hosts kết nối đến
	- Cung cấp kết nối cho các host ở trong cùng 1 mạng LAN (Local Area Network: mạng nội bộ)
	- Không cung cấp kết nối giữa các mạng LAN hoặc là kết nối với internet

# Routers (bộ định tuyến)


![[Pasted image 20261031031210.png]]

- Router là thiết bị:
	- Có ít Network interfaces hơn switch
	- được dùng để cung cấp kết nối **giữa** các mạng LAN
	- được dùng để gửi dữ liệu qua Internet



# Firewalls
![[Pasted image 20261031031741.png]]

![[Pasted image 20261031031713.png]]


- Firewall:
	- giám sát và kiểm soát traffic network dựa vào luật được config bên trong
	- Có thể đặt ở trong mạng hoặc ở ngoài mạng
	- "Next-Generation firewalls": được tích hợp nhiều tính năng hiện đại hơn để filter capabilities

- Network firewalls:
	- thiết bị phần cứng (Hardware devices) để filter traffic giữa các mạng


- Host-based firewalls:
	- Ứng dụng phần mềm lọc các traffic vào và ra 1 máy host


# Quizz

![[Pasted image 20261031032807.png]]

A sai vì router không dùng để kết nối các end hosts ngoài ra nó không có đủ 30 interface để kết nối
B sai vì firewall để filter network traffic chứ không phải để kết nối các end hosts
C đúng vì switch có tới 24+ network interfaces nên có thể kết nối trên 30 cái PC với nhau trong CÙNG 1 MẠNG LAN
D sai vì server là 1 endhost.


![[Pasted image 20261031033158.png]]

A đúng vì Iphone đóng vai trò chia sẻ dữ liệu
B sai. Nếu đề hỏi Iphone của bạn thì đúng vì iphone của bạn đóng vai trò client
C sai vì Iphone không phải là 1 mạng LAN mà chỉ có thể ở trong 1 mạng LAN


![[Pasted image 20261031033453.png]]

 A sai vì máy bạn đang xem video -> là 1 client
 B sai mặc dù đúng về mặt lý thuyết thì cả 2 client và server đều gọi chung là server nhưng mà nó không nêu rõ được vai trò của thiết bị
 Bạn là 1 client vì bạn đang xem video => chọn C


![[Pasted image 20261031033746.png]]

- Công ty cần kết nối **các mạng** với nhau => cần router để kết nối các mạng LAN
A sai: mặc dù có thể kết nối nhiều mạng với nhau nhưng mục đích là giám sát và lọc traffic
B sai: host không rõ ràng
C sai: LAN không phải là 1 thiết bị


![[Pasted image 20261031034102.png]]

- Đáp án là C vì
	- A sai do host based bảo vệ máy host chứ không bảo vệ mạng
	- B và D sai vì nó không phải là 1 loại firewall