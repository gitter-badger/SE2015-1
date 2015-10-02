# SE2015
Software Engineering 2015 

Homepage for deploy: https://cloudpainting.herokuapp.com/

==================================================================================
#Tóm tắt buổi họp ngày 02/10/2015: 
*Cách sử dụng sails js:
- Pull source code, nhánh dev;
- Vào cmd thư mục của project vừa tạo, gõ npm install một lần duy nhất để máy tải dependencies.
- Để deploy localhost:1337/ , ta gõ lệnh sails lift( cũng ở trong thư mục project)

*Chia team: 

*Phần UI-Client: Trung và Hoàng
- Làm Homepage:	làm nút bấm
- Làm màn hình vẽ: 	khung, Tên ở bên trên, làm menu

*Phần Controller-Client: Phúc, Giang
- Xử lý nét vẽ của người dùng
- Nhận thông tin server, và vẽ lại

*Phần Controller-Server: Thức, Giang
- Quản lý phòng
- Truyền tin trong khi vẽ như thế nào
- Xử lý người dùng vào sau

===================================================================================


==================================================================================
*Tóm tắt buổi họp ngày 25/9/2015: 
- Tất cả pull source code này về, checkout branch dev
- Prototype mở đầu, credit by Giang: http://imgur.com/a/nLE4D
- Chức năng chính của client đó là: tạo room, vào room, truyền tin.
- Chức năng chính của server là: truyền tin, lưu ảnh, quản lý room.
- Khi code đã chắc chắn ok, push code lên branch master, đợi 1 phút để server sẽ tự động build code, 
    Vào lại homepage https://cloudpainting.herokuapp.com/ để xem kết quả
- Quản lý source code ta dùng SourceTree: https://www.sourcetreeapp.com/download/
- Do code của cả phía client lẫn server đều dùng javascript nên tất cả ae đều cần đọc tài liệu về javascript. Thêm nữa là html5, css cho phía client. 


===================================================================================
Member:
- Nguyễn Hữu Thức(captain): MSV 13020432     Skype thuckechsu02 
- Thái Đính Phúc
- Lê Trường Giang
- Nguyễn Thành Trung (Skype: Nguyentrungpro95)
- Bùi Văn Hoàng

Khởi đầu cần thiết:
- Skype: http://www.skype.com/de/download-skype/skype-for-computer/
    Liên lạc, trao đổi teamwork. Tạo nick và chỉnh sửa lại file này để biết nick skype của nhau
- HTML5, CSS: http://www.w3schools.com/html/html5_intro.asp
    Sơ qua về HTML5, cách sử dụng các thẻ
- HTML5 Canvas: http://www.w3schools.com/html/html5_canvas.asp
    Ứng dụng vẽ thì cần phải học cái này nữa :)
    
Ý tưởng ban đầu: Ứng dụng vẽ trực tuyến dành cho một nhóm người. Dự định chúng ta sẽ cần kết hợp một nhóm làm server và một nhóm làm mobile client(Sẽ thảo luận kỹ ở tuần sau, nếu ai có ý tưởng hay hơn cứ đề xuất)


a [Sails](http://sailsjs.org) application
