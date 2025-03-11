
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

![Setting](https://github.com/v-hkopparala/v-hkopparala/blob/26cf3e21a5e7b9989d41e37d9d1ec1cffae08433/Screenshot%20(2).png)

Step3: - Click on Access control

![access_control](https://github.com/v-hkopparala/v-hkopparala/blob/546dfa049122ff2c39286172432f62ae90ced096/Screenshot%20(3).png)

Step4: - Click on Add option and select service account as shown below

![add_option](https://github.com/v-hkopparala/v-hkopparala/blob/e375cbb94737d18f7629678ac272eeb648aa746d/Screenshot%20(4).png)

Step5: - Provide the service account name and assign a role

![New_Service_account](https://github.com/v-hkopparala/v-hkopparala/blob/5a74a3de98e96e94e26e5c0e0df42f81641b93ac/Screenshot%20(5).png)

Step6: - Provide Access Key Name as per your convenience

![Accesskey_details]()

Step7: - Click on Save and create which will provide you the Access key ID and Secret Key

![Accesskey_results]()

Step 8: - Use Access Key ID as username and Secret Key as password on the Data connector page


