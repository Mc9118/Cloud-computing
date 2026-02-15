# Cloud-computing

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: MAYANK CHAUDHARY 

**INTERN ID**: CTIS4801

**DOMAIN**: CLOUD COMPUTING 

**DURATION**: 4WEEKS 

**MENTOR**: NEELA SANTOSH 



 **TASK 1** - **CREATE AND CONFIGURE CLOUD STORAGE ON AWS S3 OR GOOGLE CLOUD STORAGE .**


STEPS I HAVE PERFORM HERE :-

1. AWS Login and S3 Access

Logged into the AWS Management Console.

Navigated to the S3 service.

Accessed the “Buckets” section.

2. Creation of S3 Bucket

Clicked on “Create Bucket”.

Provided a globally unique bucket name.

Selected the region: Asia Pacific (Mumbai) – ap-south-.

Kept default security settings (Block Public Access enabled).

Enabled server-side encryption (SSE-S3).

Successfully created the bucket.

3. Uploading Example Files

Opened the created bucket.

Uploaded sample files such as:

Text file (.txt)
PDF file
Image file

Verified that files were successfully stored in the bucket.

4. Access Permission Configuration

Verified that the bucket was private by default.

Reviewed the “Permissions” tab.

Understood how public access can be controlled.

Ensured secure configuration by keeping Block Public Access enabled.

Deliverable Achieved

Successfully created and configured an S3 bucket.

Uploaded example files to cloud storage.

Configured and verified access permissions.

Demonstrated understanding of secure cloud storage practices.

 what's the Learning Outcomes

Through this task, the following concepts were learned:

Understanding of cloud storage and object storage.

Creation and configuration of AWS S3 buckets.

Region selection and its importance.

File upload and object management in S3.

Security best practices (private bucket configuration).

Basics of access control in cloud environments.

Conclusion

This task provided practical exposure to AWS cloud storage services. By creating and configuring an S3 bucket, uploading files, and managing access permissions, a foundational understanding of cloud storage architecture and security was achieved. This hands-on experience strengthens knowledge of cloud infrastructure and real-world deployment practices.



##output
<img width="1920" height="1062" alt="Image" src="https://github.com/user-attachments/assets/4fc2ba5d-b05b-48d7-a6ab-e9a4fb899008" />



**Task 2** : **Cloud Monitoring and Alerts using AWS CloudWatch**

Objective

The objective of this task was to set up monitoring for a cloud-based application using AWS CloudWatch. The task involved configuring metrics tracking, creating a monitoring dashboard, and setting up alerts for performance thresholds.

Introduction

Amazon CloudWatch is a monitoring and observability service provided by AWS. It collects metrics, logs, and events from AWS resources and allows users to monitor system performance, detect anomalies, and configure automated alerts.

**Implementation Steps:-**

1. EC2 Instance Setup

A cloud-based application environment was simulated by launching a t2.micro EC2 instance running Amazon Linux.

2. Monitoring Metrics

CloudWatch automatically collected performance metrics such as:

CPU Utilization

Network In and Out

Disk Read and Write operations

These metrics were analyzed to understand instance behavior.

3. Dashboard Creation

A custom CloudWatch dashboard was created to visualize:

CPU Utilization

Network traffic metrics

The dashboard provided real-time graphical representation of system performance.

4. Alert Configuration

A CloudWatch alarm was configured with the following:

Metric: CPU Utilization

Threshold: Greater than 70%

Evaluation period: 5 minutes

An SNS topic was created to send email notifications when the threshold condition is met.

Deliverables Achieved

Successfully monitored EC2 instance metrics.

Created a custom CloudWatch dashboard.

Configured automated alerts.

Enabled email notifications using SNS.

**Learning Outcomes:-**

Understanding of cloud monitoring concepts.

Practical experience with AWS CloudWatch.

Knowledge of alert configuration and threshold management.

Insight into real-world DevOps monitoring practices.

**Conclusion:-**

This task provided hands-on experience in cloud monitoring and alert configuration using AWS CloudWatch. By creating dashboards and alerts, the importance of proactive monitoring in maintaining cloud infrastructure reliability and performance was demonstrated.

**Output**

<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/640fb196-6ba1-4b13-8351-417a6f3713be" />

<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/c4ff10f4-fb4b-4fb5-b8e7-a10568ccb574" />

<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/c6efd132-19ef-4562-8c18-b0e3ad2aa943" />

<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/2548e475-4868-4e28-8f9b-a0aab72e37fa" />

<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/fa996628-8662-4d55-b7f2-91002f52fd7a" />



  **Task 3** : - **DESIGN A MULTI-CLOUD ARCHITECTURE WHERE SERVICES ARE DISTRIBUTED ACROSS TWO CLOUD PROVIDERS.**

  **Objective -**

To design and demonstrate a multi-cloud architecture where services are distributed across two cloud providers and show interoperability between platforms.

**Cloud Providers Used -**

Amazon Web Services (AWS)

GitHub API (External Cloud Service)

**Architecture Design -**

AWS EC2 instance was launched in the US-East-1 region.

The EC2 instance acts as the primary cloud computing environment.

From the EC2 terminal, we connected to an external cloud-based API (GitHub API).

This demonstrates interoperability between AWS cloud infrastructure and another cloud service platform.

Practical Implementation Steps:

Launched an EC2 instance (Amazon Linux 2023).

Connected to the instance using EC2 Instance Connect.

**Executed the following command-**

curl https://api.github.com/users/octocat


The EC2 instance successfully retrieved JSON data from the GitHub cloud API.

**Result-**

The successful API response confirms that:

The AWS cloud environment can communicate with external cloud platforms.

Multi-cloud interoperability has been successfully demonstrated.

The architecture supports cross-platform service communication.

**Conclusion-**

This implementation successfully demonstrates a simple multi-cloud architecture where AWS EC2 interacts with an external cloud service (GitHub API), proving interoperability between cloud platforms.

**Output -**

<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/0586b3b8-69fb-450d-8892-f56e948c5ad0" />

<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/95438255-7b57-466d-bb43-a7078a34e673" />

<img width="1920" height="1200" alt="Image" src="https://github.com/user-attachments/assets/b164aa76-e83f-45a0-86dd-36dc3328390b" />

  
This architecture can be extended further by integrating Azure or Google Cloud services for storage, monitoring, or database services to build a fully distributed multi-cloud system.
