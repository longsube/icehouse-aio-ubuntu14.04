# Cài đặt & HDSD OpenStack Icehouse AIO
#### Nhóm thực hiện:

| Họ và Tên        | Nick Skype | Email | 
|------------------|------------|-------|
|Tô Thành Công     | tu0ng_c0ng | tcvn1985@gmail.com |
|Hoàng Đình Quân   | hdquan2014 | d0m0reg00dthing@gmail.com |
| VietStacker      | vietstack  | vietstack@gmail.com

#### Thông tin phiên bản

| Ngày tạo	   | Tên Phiên Bản |   Thông tin phiên bản   | Người thay đổi       |               Chú ý               |
| -------------|---------------|-------------------------| ---------------------|--------------|------------------------| 
| 30/06/2014   |    Mầm ươm    | - Tạo các scritp đầu tiên <br> - Sửa lại các script từ repos gốc <br> - Thêm file config.cgf| Hoàng Đình Quân <br> Tô Thành Công | Tổng hợp lại từ github của Công|
| 05/07/2014   |               | - Bổ sung các lệnh sleep khi cài dịch vụ <br> - Bổ sụng lệnh reset RABBITMQ <br> - Bổ sung file config-after-neutron.cfg |  Tô Thành Công         |    |
| 21h00 05/07/2014 | | - Bổ sung các lệnh reset neutron vào rc.local | Tô Thành Công | | 

#### Giới thiệu
Hướng dẫn này được cung cấp giúp các bạn đã tìm hiểu tổng quan về Cloud Computing (dựa theo định nghĩa trong tài liệu NIST - Cloud Computing) và OpenStack có thể triển khai một cách gọn gàng và đủ tính năng tối thiểu cho mục đích trải nghiệm và tìm hiểu cách sử dụng OpenStack.

Hướng dẫn được triển khai trên môi trường LAB (VMware Workstation), trên 1 máy chủ duy nhất có hỗ trợ công nghệ ảo hóa, x64. Trong phiên bản "Nhiệt & Đam Mê" của hướng dẫn này, mình tham khảo nguồn chính là docs của OpenStack và GOOGLE nên xin phép không trích dẫn lại các link khác ở đây. Một số script mình có chỉnh sửa lại đê tối giản các dòng lệnh và giải thích trong từng script.

Theo docs OpenStack, mô hình chuẩn là 03 node (Controller, Compute, Network) nếu sử dụng Neutron cho thành phần Networking. Nhưng vì nhiều bạn mới tìm hiểu không đủ tài nguyên để triển khai và một số bạn muốn tham gia phát triển các project hoặc tìm hiểu các tùy chọn cho cấu hình do vậy mình quyết định tổng hợp hướng dẫn này trên một node (một máy chủ duy nhất).

Các core project trong phiên bản hướng dẫn này gồm: KEYSTONE, GLANCE, NOVA, NEUTRON, CINDER, HORIZON. Trong phiên bản tiếp theo mình sẽ bổ sung các project khác của OpenStack sau khi test thành công.

Trong các script mình có sao lưu các file cấu hình gốc, sử dụng các lệnh về thao tác chuỗi, phân quyền, khai báo biến .... để thực hiện việc cấu hình cho OpenStack, các bạn có thể tham khảo trong từng script.


## [Hướng dẫn cài đặt OpenStack AIO Ubuntu 14.04](https://github.com/longsube/icehouse-aio-ubuntu14.04/blob/master/hd-caidat-openstack-icehouse-aio.md)

## [Hướng dẫn sử dụng OpenStack AIO]


[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/6lJwvGY1WLk/0.jpg)](http://www.youtube.com/watch?v=6lJwvGY1WLk)


