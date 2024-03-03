---
title : "Chuẩn bị"
date :  "`r Sys.Date()`" 
weight : 2 
chapter : false
pre : " <b> 2. </b> "
---

## Source code để deploy lên EBS

Bạn có thể sử dụng bất kỳ ngôn ngữ lập trình nào để triển khai trên EBS. Trong bài workshop này, tôi sẽ sử dụng Java để triển khai ứng dụng web lên EBS.

### File .bak của database

Bạn cần chuẩn bị một tệp .bak của bất kỳ cơ sở dữ liệu nào. Trong bài workshop này, Mình sẽ sử dụng MSSQL.

Example with MSSQL
#### Kết nối với cơ sở dữ liệu và nhấp chuột phải vào cơ sở dữ liệu bạn cần xuất tệp .bak từ -> chọn task -> Back up
![DTB](/images/2/Screenshot2024-02-29130504.png)

#### Chọn địa chỉ để lưu tệp và nhấp vào add
![DTB](/images/2/Screenshot2024-02-29130559.png)

### Đầu tiên, hãy tạo một vai trò cung cấp một số quyền cho việc làm việc với dịch vụ EBS như bên dưới.

#### Truy cập IAM -> Role -> Tạo role -> Chọn AWS Service -> Chọn EC2 làm dịch vụ và trường hợp sử dụng -> Chọn ba chính sách dưới đây -> Cung cấp tên cho vai trò và sau đó tạo.

![IAM](/images/1/createrole.PNG)

![IAM](/images/1/step1role.PNG)

![IAM](/images/1/pickrole.PNG)

![IAM](/images/1/createrole.PNG)

![IAM](/images/1/result.PNG)

### Được rồi, bây giờ chúng ta di chuyển sang phần tiếp theo.
