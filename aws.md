# AWS

## Cloud Practicioner

- [ ] **Cloud Computing**

  - [ ] What is cloud computing?

  - [ ] The 6 advantages of cloud computing
    - [ ] **Trade capital expense for variable expense** - pay for what you consume instead of investing in something you don'y fully utilize
    - [ ] **Benefit from massive economies of scale**
    - [ ] **Stop guess about capacity** - Cloud scales with your needs
    - [ ] **Increase speed and agility** - You can use the cloud to quickly build platforms using architectures such as serverless for example
    - [ ] **Stop spending money running and maintaining data centers** - Focus on what you want instead of focusing on managing infrastructure
    - [ ] **Go global in minutes** - Easily deploy your application in multiple regions around the world which results in better experience (like lower latency) for users of your app

  - [ ] 3 Types of cloud computing
    - [ ] **Infrastructure as a service (IAAS)** - You are managning the server. It can virtual or physical. The provider (e.g. Amazon) will have no access to your server. EC2 is an example of IAAS.
    - [ ] **Platform As a service (PAAS)** - Someone else manages the underlying hardware and OS. You focus on the application side. Heroku and Google app engine are examples of PAAS.
    - [ ] **Software As A service (SAAS)** - You only worry about the software. As opoosed to PAAS, you don't have to worry about the installation and the setup of the application. You just have to use the software itself.

  - [ ] 3 types of cloud computing deployments
    - [ ] **Public Cloud** - AWS, Azure & GCP
    - [ ] **Hybrid** - Mixture of public and private.
    - [ ] **Private Cloud / On Premise** - You manage it in your datacenter. OpenStack for example.
  
- [ ] **Global Infrastructure**
    
    - [ ] **Availability Zone** is one or more data centres, each with redundant power, networking and connectivity, housed in separate facilities.
    - [ ] **Region** is a geographical/physical area. Region consists of two or more availability zones
- [ ] **Edge locations** are endpoints for AWS which are use for caching content.
    
- [ ] **IAM**
  
  - [ ] IAM (Identity Access Management) is global. You do not need to specify region when dealing with IAM related resources
  - [ ] There are 3 ways to access the AWS platform
  
    - [ ] Console
    - [ ] Programmatically(CLI)
    - [ ] Software Developers Kit (SDK)
  - [ ] Root account is the email address you to set up the AWS account and it has full permissions
  - [ ] Root account should not be given to anyone, instead the root account should create users
  
- [ ] **S3**

  - [ ] Simple Storage Service
  - [ ] S3 is a secure, highly scalable object storage
  - [ ] S3 is object-based storage. The data itself is spread across multiple locations.
  - [ ] Files can be from 0 Bytes to 5 TB. There is unlimited storage.
  - [ ] Files are stored in buckets
  - [ ] Bucket name must be globally unique
  - [ ] HTTP 200 code is returned when a file is uploaded successfully to S3
  - [ ] Objects consist of:
      - [ ] **Key** - name of the object
      - [ ] **Value** - the data itself
      - [ ] **Version ID** - used for versioning
      - [ ] **Metadata** - data about the data
  - [ ] Data consistency
  
  


## Questions

Name | Description
:------|:------:
[AWS interview questions and answers](https://www.besanttechnologies.com/aws-interview-questions-and-answers) | 250 AWS interview questions