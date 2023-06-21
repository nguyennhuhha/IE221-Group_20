# IE221-Group_20
## Đối với drive: có thể tải thư mục WEBSILL chứa 2 folder là env là môi trường và webSill là code của trang web
## Hoặc chỉ tải thư mục webSill bên trong WEBSILL và sau đó cài đặt môi trường env  
## Đối với github: tải về webSill và cài đặt môi trường ảo
Bản github chỉ có thư mục webSill  
Bản drive có đầy đủ thư mục env đến webSill
### Cài môi trường với câu lệnh:
py -m venv env  
sau đó ta sẽ có thư mục env đặt nó vào cùng thư mục chứa webSill sau đó thực hiện các bước dưới 
## Yêu cầu tải Xampp (tạo localhost) nhấn nút start bên cạnh 2 chức năng: Apache và MySQL  
![image](https://github.com/nguyennhuhha/IE221-Group_20/assets/94069476/d4e78959-0974-4965-870a-e0adac07bb3d)  
Sau khi start ta có như hình:  
![image](https://github.com/nguyennhuhha/IE221-Group_20/assets/94069476/a51de721-0d7a-4c86-ba1c-1dd5c18987ab)  

### Ở thư mục WEBSILL lớn: kích hoạt môi trường với câu lệnh
.\env\Scripts\activate  
![image](https://github.com/nguyennhuhha/IE221-Group_20/assets/94069476/8c57024d-06c4-4ee4-b1fb-7f581cb03ddc)  
môi trường sẽ được kích hoạt như ảnh:  
![image](https://github.com/nguyennhuhha/IE221-Group_20/assets/94069476/3c66e1dc-ba7e-426a-9c72-1ac2f415930a)

### Đi vào thư mục webSill bằng lệnh: 
cd webSill   
để được đường dẫn như hình:  
![image](https://github.com/nguyennhuhha/IE221-Group_20/assets/94069476/4bfda228-5faf-4505-b44a-669068b908db)  

### Runserver với câu lệnh:  
python manage.py runserver  
đường link được hiển thị như ảnh và click vào để vào trang web  
![image](https://github.com/nguyennhuhha/IE221-Group_20/assets/94069476/33346dee-cb0b-4f73-89a5-0dc0019fd040)  
### Xem trang admin với đường dẫn thêm sau là /admin/:
![image](https://github.com/nguyennhuhha/IE221-Group_20/assets/94069476/0861bd2b-6a57-4288-8e44-765b992bbbb0)  
Sign in với username: admin2 / password: Nhuha123
