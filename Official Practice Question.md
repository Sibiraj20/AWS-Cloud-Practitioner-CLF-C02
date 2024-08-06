# AWS Certified Cloud Practitioner Official Practice Question Set (CLF-C02)

## AWS Services and Descriptions

- **AWS CodeArtifact**: Managed artifact repository service that stores and shares software ready for deployment. Not a source code management service.
- **AWS CodeBuild**: Service to automatically compile source code, run unit tests, and produce software packages ready for deployment. Not a code management service.
- **AWS CodePipeline**: Manages the movement of code between individual services. Not a source code storage service.
- **AWS CodeCommit**: Source code version control service that helps users store and manage developers' source code in AWS.
- **AWS Global Accelerator**: Networking service that improves users’ network traffic performance by up to 60% using AWS global network infrastructure. Not a relational database.
- **Amazon DynamoDB**: Fully managed NoSQL database service providing fast and predictable performance with seamless scalability. Not a relational database.
- **Amazon Aurora**: MySQL- and PostgreSQL-compatible relational database built for the cloud, combining the performance and availability of traditional enterprise databases with the simplicity and cost-effectiveness of open-source databases.
- **Amazon Elastic Block Store (Amazon EBS)**: High-performance block-storage service used with Amazon EC2 for throughput- and transaction-intensive workloads. Not a relational database.
- **Amazon CloudWatch**: Monitors AWS resources and applications in real-time, can be used with AWS CloudTrail to monitor and receive alerts about console sign-in events involving the AWS account root user.
- **AWS Config**: Assesses, audits, and evaluates the configurations of AWS resources. Cannot alert about console sign-in events involving the AWS account root user.
- **AWS Trusted Advisor**: Provides real-time guidance to help provision resources according to AWS best practices. Cannot alert about console sign-in events involving the AWS account root user.
- **AWS Identity and Access Management (IAM)**: Manages access to AWS services and resources securely. Cannot alert about console sign-in events involving the AWS account root user.

## Practice Questions and Answers

1. **How does AWS charge for AWS Lambda usage once the free tier has been exceeded?**
   - By the time it takes for the Lambda function to run
   - By the number of requests made for a given Lambda function

2. **A user deploys an Amazon RDS DB instance in multiple Availability Zones. This strategy involves which pillar of the AWS Well-Architected Framework?**
   - Reliability

3. **Each department within a company has its own independent AWS account and its own payment method. The company needs to centralize departmental governance and consolidate payments.**
   - Create an organization in AWS Organizations with all features enabled within one account. Invite all accounts to join the organization.
   - Organizations provide centralized governance and billing for an AWS environment, including multiple accounts.

4. **What are the advantages of deploying an application with Amazon EC2 instances in multiple Availability Zones? (Select TWO.)**
   - Increasing the availability of the application
   - Availability Zones are designed for physical redundancy and to provide resilience with uninterrupted performance.

5. **Which tasks are the customer's responsibility according to the AWS shared responsibility model? (Select TWO.)**
   - Configure IAM users according to the principle of least privilege.
   - Configure an Amazon S3 bucket to allow public access.

6. **A company wants to create a learning application for students. The learning application must give students the option to choose a button to have the text read out loud to them.**
   - **Correct**: 
     - **Amazon Polly**: Machine learning service that converts text to speech, providing the ability to read text out loud.
   - **Incorrect**:
     - **Amazon Transcribe**: Converts audio data to text.
     - **Amazon Translate**: Language translation service.
     - **Amazon Textract**: Extracts text from scanned documents.

7. **A company wants to establish a consistent and private connection from the company's on-premises data center to the AWS Cloud.**
   - **Correct**: 
     - **AWS Direct Connect**: Links your internal network to a Direct Connect location through a standard Ethernet fiber-optic cable, providing a consistent and private connection.
   - **Incorrect**:
     - **AWS Client VPN**: Connects individual laptops to AWS, not an entire data center.
     - **AWS Connect**: Omnichannel cloud contact center for customer service.
     - **AWS Site-to-Site VPN**: Creates an encrypted network path using the internet, not providing a consistent and private connection.

8. **A company has an on-premises Linux-based server with an Oracle database that runs on it. The company wants to migrate the database server to run on an Amazon EC2 instance in AWS.**
   - **Correct**: 
     - **AWS Application Migration Service (AWS MGN)**: Automated lift-and-shift solution to migrate physical servers and databases to EC2 instances in AWS.
   - **Incorrect**:
     - **AWS Database Migration Service (AWS DMS)**: Migrates data from an on-premises database to a database in AWS.
     - **AWS Migration Hub**: Helps plan and track application migrations.
     - **AWS Application Discovery Service**: Collects information to help plan a migration to AWS.

9. **A company is hosting a static website from a single Amazon S3 bucket.**
   - **Correct**: 
     - **Amazon CloudFront**: Speeds up the distribution of web content by caching content in edge locations.
   - **Incorrect**:
     - **AWS Elastic Beanstalk**: Deploys and scales web applications but does not reduce website latency.
     - **Amazon DynamoDB Accelerator (DAX)**: Reduces response times from a DynamoDB table but cannot host static websites.
     - **Amazon Route 53**: Directs traffic to S3 buckets but cannot reduce latency with a single bucket.

10. **Which credential components are required to gain programmatic access to an AWS account? (Select TWO.)**
    - An access key ID
    - A secret access key

11. **What is the MINIMUM AWS Support plan that provides technical support through phone calls?**
    - **Correct**: 
      - **Business**: Allows calling or chatting with technical support.
    - **Incorrect**:
      - **Enterprise**: Provides phone support but is not the minimum plan.
      - **Developer**: Allows only email support tickets, no phone support.
      - **Basic**: Provides non-technical support but no technical phone support.

12. **Which AWS service allows customers to purchase unused Amazon EC2 capacity at an often discounted rate?**
    - **Correct**: 
      - **Spot Instances**: Access unused EC2 capacity at a discounted rate.
    - **Incorrect**:
      - **Reserved Instances**: Reserve capacity but not necessarily unused capacity.
      - **On-Demand Instances**: Default purchase option, not discounted.
      - **Dedicated Instances**: Run on dedicated hardware, not discounted.

13. **What are the benefits of using the AWS Cloud for companies with customers in many countries around the world? (Select TWO.)**
    - Companies can deploy applications in multiple AWS Regions to reduce latency.
    - Amazon CloudFront has multiple edge locations around the world to reduce latency.

14. **Which of the functionalities are characteristics of Amazon S3? (Select TWO.)**
    - An object store
    - A durable file system

15. **A company requires an encrypted connection between the company's on-premises servers and AWS. The connection must use the company's existing internet connection.**
    - **Correct**:
      - **AWS Site-to-Site VPN**: Creates an encrypted network path using the internet.

16. **A user needs to automatically discover, classify, and protect sensitive data stored in Amazon S3.**
    - **Correct**:
      - **Amazon Macie**: Automated security assessment service for data in S3.
    - **Incorrect**:
      - **Amazon Inspector**: Assesses security for applications on EC2 instances.
      - **Amazon GuardDuty**: Detects threats but does not classify S3 data.
      - **AWS Secrets Manager**: Protects access secrets, not classifying S3 data.
