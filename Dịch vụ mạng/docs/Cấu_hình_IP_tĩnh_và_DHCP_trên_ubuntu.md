> Để cấu hình ip tĩnh hoặc dhcp trên ubuntu thì ta phải truy cập với quyền cao nhất là sudo
- cấu hình ip tĩnh 
```
sudo nano /etc/netowrk /interfaces : Truy cập vào card mạng
auto eth1  : khởi động card mạng cùng hệ thống
iface eth1 inet static : để ip chế độ static
address địa chi ip 
netmask gia trị 
```

- Cấu hình dhcp
```
sudo nano /etc/network/interfaces : truy cập vào card mạng
auto eth1 : khởi động card mạng cùng hệ thống
iface eth1 inet dhcp :  để chế độ dhcp 
```		
		
		
