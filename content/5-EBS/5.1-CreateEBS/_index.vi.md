---
title : "Tạo EBS"
date :  "`r Sys.Date()`" 
weight : 1
chapter : false
pre : " <b> 5.1 </b> "
---

#### EBS Service

1. Truy cập dịch vụ **EBS Service**, sau đó chúng ta chọn "create application" -> Chúng ta điền thông tin
   
   ![Create EBS](/images/5-EBS/5.2-ebs/Createapp.PNG?featherlight=false&width=90pc)

   ![Create EBS](/images/5-EBS/5.2-ebs/datnamee.PNG?featherlight=false&width=90pc)

2. Chúng ta chọn tab ->  chúng ta nhấp vào "create enviroment"
   
   ![Create RDS](/images/5-EBS/5.2-ebs/createenv.PNG?featherlight=false&width=90pc)

   -Step 1: Điền thông tin vào 2 mục thông tin Application and Enviroment -> Platform: chọn mã chúng ta cần triển khai-> Application code: chọn tải lên mã, điền phiên bản, tải lên mã với 2 tùy chọn (tệp cục bộ hoặc S3) -> Next step

   ![Create RDS](/images/5-EBS/5.2-ebs/step1config.PNG?featherlight=false&width=90pc)

   ![Create RDS](/images/5-EBS/5.2-ebs/step12.PNG?featherlight=false&width=90pc)

   ![Create RDS](/images/5-EBS/5.2-ebs/step13.PNG?featherlight=false&width=90pc)

   -Step 2: Chọn create and use service role -> EC2 instance profile : chúng ta chọn role trong bước đầu tiên chúng ta đã tạo -> Next step

   ![Create RDS](/images/5-EBS/5.2-ebs/step2.PNG?featherlight=false&width=90pc)

   -Step 3 and 4 (Optional): Trong các bước này, chúng ta có thể cấu hình theo ý muốn, hoặc chúng ta có thể chọn bỏ qua chúng.

   ![Create RDS](/images/5-EBS/5.2-ebs/Capture.PNG?featherlight=false&width=90pc)

   -Step 5: Trong bước này, cuộn xuống trang cuối cùng và cấu hình lại thuộc tính môi trường. Sau đó, lấy thông tin từ dịch vụ RDS, chẳng hạn như Endpoint, tên cơ sở dữ liệu, tên người dùng và mật khẩu. Tiếp tục sang bước tiếp theo và cuối cùng để xem lại.

   ![Create RDS](/images/5-EBS/5.2-ebs/step5.PNG?featherlight=false&width=90pc)

    -Step 6: Chúng ta xem lại thông tin và click submit

    ![Create RDS](/images/5-EBS/5.2-ebs/step6.PNG?featherlight=false&width=90pc)

3. Vui lòng đợi một chút trong khi EBS triển khai mã của bạn.
   
   ![Create RDS](/images/5-EBS/5.2-ebs/wating.PNG?featherlight=false&width=90pc)