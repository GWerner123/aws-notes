# Introduction to Cloud 101
---------------------------

Cloud computing is basically just delivering technology resources or tools over the internet to users as they need them, and users only have to pay for what they actually use.

Modern computing uses the client-server model. Think about it like this: a customer asks a server for something at a restaurant. The server goes and fulfills the request that the customer (or client) made and returns it back to the customer. This is the same with a browser or desktop application (the client) and a server. Amazon Elastic Compute Cloud or EC2 is a type of virtual server.

There are many benefits of cloud computing. It saves you money because you only pay for the data storage and the computing power that you are actually using, you don't have to build and maintain your own massive data centers, and because so many businesses use AWS the prices to use it are only getting cheaper. It also improves efficiency and productivity because you don't have to guess the capacity of what your data center can handle anymore, you can implement new tools and technologies into your business instantly rather than having to build out your own data centers with new stuff, and you can reach a global audience because AWS has regions all over the world to help being services to customers with very little delay.

There are different types of ways to deploy to the cloud based on what your business needs. The different deployment models include Infrastructure as a service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS). The different deployment strategies include Cloud, Hybrid, and On-premises.

IaaS is cloud computing in the most granular form and it gives you the most control over your IT resources. Usually IaaS provides access to data storage space, computers, and networking features. Some common AWS services that are considered IaaS include: Amazon EC2, Amazon Simple Storage Service (Amazon S3), Amazon Relational Database (Amazon RDS), and Amazon Route 53.

PaaS is where organizations that are using AWS do not need to worry about managing the infrastructure like hardware and operating systems (those things are taken care of for them) but rather they can focus solely on deploying and managing new and existing applications for their business. Example of PaaS is AWS Elastic Beanstalk which allows you to quickly deploy and scale web applications.

SaaS is a completed software product where all you have to do is use that software. You don't need to worry about managing anything; just use the software!

Cloud deployment strategy is where you can migrate your organization's applications into the cloud or you can create new applications in the cloud. You can either get really granular with it and manage the infrastrucutre, or you can build and deploy quickly with services that make it easy to do so. Either way, everything will be in the cloud.

A Hybrid deployment strategy is where a company connects their on-premises infrastructure with specific cloud services that are useful for their business needs. They might do this because of certain regulations that require them to keep records on-premises or just because certain applications might work best on-premises for whatever reason. Luckily they can still integrate services that they need from the cloud to their infrastructure to improve their cost and efficiency.

On-premises deployment is sometimes also called private cloud deployment. This is where everything is kept on premises in an organizations own data center but they can still deploy resources to use for their business by using virtualization and application management technologies.

AWS is a huge cloud infrastructure with over 175 different services for all sorts of use cases. AWS and the customer split the responsibility for programming as well as for cybersecurity.

Categories of services that AWS includes: compute, storage, database, analytics, networking & content delivery, developer tools, business applications, management & governance, machine learning, internet of things, and security.

AWS global infrastructure includes: regions, availability zones, and edge locations.

Region: physical location in the world where AWS data centers are clustered together. A group of data centers that go together are called an availability zone. Each AWS region has multiple separate availability zones.

Availability zone: area within region that has one or more data centers (usually has three). Availability zones house all hardware that AWS offers. Availability zones are separated up to 60 miles apart from another availability zone. Availability zones are interconnected.

When building architecture in the cloud it is important to plan for failure.

AWS availability zones help you plan for failure by: 

1. when you store a file in S3 that file is redundantly copied to every availability zone in that region so that if one goes down, the file still exists.

2. computing resources are spread throughout multiple availability zones in a region so that if one goes down, your architecture is still up and running

3. you ca configure database for multi-AZ deployment so that if your main database fails, one of the ones in a healthy availability zone becomes your primary database and everything still functions.

You can also plan for failure on a global scale by mirroring your architecture with scaled down resources in another region. If your main region goes down, you can scale up the resources in that other region to account for the loss without actually losing your ability to keep running for your customers.

AWS shared responsibility model means that AWS is responsible for the security *of* the cloud, while the customer is responsible for the security *in* the cloud.

The AWS Well-Architected Framework is a framework that is based on analyzing thousands of customer frameworks that were built in the AWS cloud to determine what the best way is to build the most secure, high-performing, resilient, and cost-effective infrastrucutre possible in the AWS cloud.

Five pillars of the AWS Well-Architected Framework:

1. Operational excellence
2. Security
3. Reliability
4. Performance Efficiency
5. Cost Optimization

1. Operational excellence - ability to run and monitor systems and contiunally improve them by performing operations as code, annotating documentation, anticipating failure, and making small but reversible changes frequently.

2. Security - ability to protect info, systems, and assets by automating security best practices when possible, applying security at all layers, and protecting data in transit and at rest

3. Reliability - ability of a system to recover from disruptions, dynamically acquire computing resources as needed, and mitigate disruptions to network by testing recovery procedures, scaling horizontally, and automatically recovering from failure.

4. Performance Efficiency - ability to use and maintain computing resources efficiently by evaluating performance efficiency through frequent experimentation, using serverless architectures, and desigining systems to be able to go global in minutes.

5. Cost Optimization - ability to run systems to deliver business value at lowest price point by optimizing cost through use of a consumption model, analyzing expenses, and using managed services to reduce cost

AWS well-architected tool can help you by having you answer questions about the five pillars and your current architecture.

Total cost of ownership (TCO) is combined cost of using all of the services that you are using for your business. This can be difficult but with AWS pricing calculator it can be easy!

AWS pricing models:

1. pay-as-you-go
2. save when you reserve - this is where you commit to a certain amount of time to use AWS services (like AWS compute, AWS machine learning, and AWS database services) and then you can get savings that are even better than the pay as you go model. (1-year or 3-year periods are available).
3. pay less by using more - services like Amazon S3 where pricing is tiered so that the more you use, the less you pay per GB.

AWS free tier is for learning and experimenting with AWS. There are three offerings:

1. always free - example is AWS lambda gives 1 million free requests per month, every month
2. 12 months free - some services can be used free for the first year from your sign up date
3. trials - Amazon SageMaker and Amazon GuardDuty both offer trials

AWS Billing Dashboard allows you to monitor and pay your AWS bills.

## Careers in the Cloud

AWS has millions of customers including startups as well as large corporations. That means there are tons and tons of jobs for people to help those organizations with their cloud needs.

Benefits: variety of roles and you can always switch to different ones (IT pro, sales, education, manager, startup owner, cloud contractor), high paying jobs (entry level can pay $85,000 and with experience can go up to $200,000), great work-life balance

careers:

- cloud support specialist
- solutions architect
- DevOps engineer
- big data analyst
- machine learning engineer
- application developer

- cloud consultant
- AWS account manager

- people managers
- program managers
- financial managers

- enterprise trainers
- university instructors

- small businesses
- private contractors

Solutions Architect career pathway:
1. Basic IT training (school or hands-on)
2. Coding Proficiency (Java or Python)
3. AWS Certifications
4. Entry Level Role
5. Solutions 


## AWS Core Services

AWS Cloud9 is a cloud-based IDE that lets you write, run, and debug your code in a browser! It supports many languages including python and java and javascript. It even supports Go!

You can start projects from anywhere on any device and you can code together with other people without having to commit your changes to Git.

Cloud9 Development environment is your computer and AWS Cloud9.

Cloud9 Runtime environment can either be an Amzon EC2 instance or it can be your own server.

Cloud9 Version Control system can be AWS CodeCommit repository or it can be another remote repository type like GitHub

In order to use Cloud9 you first need to set up your AWS account and create an IAM user with the right permissions.

In AWS Cloud9, a development environment is where you develop and store all of the files associated with a project you are working on and where you run the tools that allow you to do that development. In a basic application in cloud9 you might develop in an EC2 environment.

Note to self: you have to use the link that was emailed to your personal email address when you created your administrator access IAM user if you want to log in to the account as that user. It won't let you log in using the normal IAM user login page.
