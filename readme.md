
# Integrating Palo Alto Prisma Cloud CSPM into Microsoft Sentinel
## Table of contents
- [Introduction](#intro)
- [Prerequisites](#step2)

<a name="intro">

## Introduction
The Palo Alto Prisma Cloud CSPM Codeless Connector for Microsoft Sentinel enables seamless integration of Palo Alto Prisma Cloud CSPM logs with Microsoft Sentinel without the need for custom code. Developed as part of the Codeless Connector Platform(CCP), this connector simplifies the process of collecting and ingesting Cloud CSPM logs from Prisma Cloud Platform into Microsoft Sentinel.

<a name="step2">
   
## Prerequisites
The below mentioned resources are required to connect Prisma Cloud with Sentinel.
- Access Key ID
- Secret Access Key

To generate the above resources, you must following the steps.


## Prisma Cloud API Key Generation using service account 

Step1:- Login to the Prisma console portal

![Prisma_console_portal](https://github.com/v-hkopparala/v-hkopparala/blob/main/Screenshot%20(1).png?raw=true)

Step2: - Go to settings tab 

![Setting](Images/setting.png)

Step3: - Click on Access control

![access_control](Images/access_control.png)

Step4: - Click on Add option and select service account as shown below

![add_option](Images/add_option.png)

Step5: - Provide the service account name and assign a role

![New_Service_account](Images/New_Service_account.png)

Step6: - Provide Access Key Name as per your convenience

![Accesskey_details](Images/Accesskey_details.png)

Step7: - Click on Save and create which will provide you the Access key ID and Secret Key

![Accesskey_results](Images/Accesskey_results.png)

Step 8: - Use Access Key ID as username and Secret Key as password on the Data connector page


