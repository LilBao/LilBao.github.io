---
title: "Create a Elastic Beanstalk"
date: "`r Sys.Date()`"
weight: 1
chapter: false
pre: " <b> 5.1 </b> "
---

#### EBS Service

1. Access the **EBS Service**, then we select "create application" -> We fill out the information

   ![Create EBS](/images/5-EBS/5.2-ebs/Createapp.PNG?featherlight=false&width=90pc)

   ![Create EBS](/images/5-EBS/5.2-ebs/datnamee.PNG?featherlight=false&width=90pc)

2. We choose tab Enviroment -> we click "create enviroment"
   
   ![Create RDS](/images/5-EBS/5.2-ebs/createenv.PNG?featherlight=false&width=90pc)

   -Step 1: Fill the information in 2 items information Application and Enviroment -> Platform: select code we need deploy ->Application code: choose upload code, fill version, upload code with 2 options (local file or S3) -> Next step

   ![Create RDS](/images/5-EBS/5.2-ebs/step1config.PNG?featherlight=false&width=90pc)

   ![Create RDS](/images/5-EBS/5.2-ebs/step12.PNG?featherlight=false&width=90pc)

   ![Create RDS](/images/5-EBS/5.2-ebs/step13.PNG?featherlight=false&width=90pc)

   -Step 2: choose create and use service role -> EC2 instance profile : we choose the role in first step we created -> Next step

   ![Create RDS](/images/5-EBS/5.2-ebs/step2.PNG?featherlight=false&width=90pc)

   -Step 3 and 4 (Optional): In these steps, we can configure what we want, or we can choose to skip them.

   ![Create RDS](/images/5-EBS/5.2-ebs/Capture.PNG?featherlight=false&width=90pc)

   -Step 5: In this step, scroll to the last page and configure the environment property overwrite. Then, retrieve the information from the RDS service, such as Endpoint, dbname, username, and password. Proceed to the next and last step for review.

   ![Create RDS](/images/5-EBS/5.2-ebs/step5.PNG?featherlight=false&width=90pc)

    -Step 6: We review the information and click submit

    ![Create RDS](/images/5-EBS/5.2-ebs/step6.PNG?featherlight=false&width=90pc)

3. Please wait a moment while EBS deploys your code. 
   
   ![Create RDS](/images/5-EBS/5.2-ebs/wating.PNG?featherlight=false&width=90pc)