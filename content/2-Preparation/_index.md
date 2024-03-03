---
title : "Prepare"
date : "`r Sys.Date()`"
weight : 2
chapter : false
pre : " <b> 2. </b> "
---

### Source code deloy in EBS

You can use any programming language to deploy on EBS. In this workshop, I am using Java to deploy a web application to EBS.

### File .bak of database

You need to prepare a .bak file of any database. In this workshop, I am using MSSQL.

Example with MSSQL
#### Connect to database and click right mouse in database you need export file .bak -> choose task -> Back up
![DTB](/images/2/Screenshot2024-02-29130504.png)

#### Choose address save file and click add
![DTB](/images/2/Screenshot2024-02-29130559.png)

### First, let's create a role providing some permissions to work with the EBS service as below.

#### Enter IAM -> Role -> Create role -> Select AWS Service -> Select service and use case we choice EC2 -> Select 3 policies below -> Provide a name for the role and then create it.

![IAM](/images/1/createrole.PNG)

![IAM](/images/1/step1role.PNG)

![IAM](/images/1/pickrole.PNG)

![IAM](/images/1/createrole.PNG)

![IAM](/images/1/result.PNG)

### Alright, now we move on next session


