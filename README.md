# Simple Storage Service(S3)


In Amazon Web Services (AWS), an S3 bucket refers to a storage resource that allows you to store and retrieve data. S3 stands for Simple Storage Service, and it is a highly scalable and durable object storage service provided by AWS.

**Here are some key features and characteristics of S3 buckets:**

* **Object Storage:** S3 buckets are used to store objects, which can be files of any type or size. Each object is identified by a unique key (which includes the file name) within the bucket.

* **Scalability:** S3 buckets can store an unlimited number of objects, providing virtually unlimited storage capacity. You can create multiple buckets as per your requirements.

* **Durability and Availability:** S3 is designed to provide 99.99% durability for your objects. This means that your data is highly resilient and unlikely to be lost. S3 also ensures high availability, allowing you to access your objects anytime, anywhere.
<p align="center">
<img src="https://github.com/jijinmichael/S3-and-IAM-user/assets/134680540/776ed61a-28fe-41fd-ba7c-d672f58daaec"></p>

* **Security:** S3 offers several security features to protect your data, including server-side encryption, access control policies, bucket policies, and integration with AWS Identity and Access Management (IAM). You can control who has access to your bucket and the objects within it.

* **Versioning:** S3 provides the option to enable versioning for your bucket, which allows you to keep multiple versions of an object over time. This helps in maintaining a history of changes and recovering from accidental deletions or modifications.

* **Lifecycle Management:** You can define lifecycle policies for your S3 buckets to automate the transition of objects between different storage classes, such as moving infrequently accessed data to cheaper storage options like S3 Glacier or S3 Glacier Deep Archive.

* **Data Transfer:** S3 supports seamless data transfer both into and out of the bucket. You can upload data using various methods, including the AWS Management Console, command-line tools, or programmatically using AWS SDKs.

S3 buckets are widely used for various purposes, such as hosting static websites, storing backups, distributing large files, data archiving, and serving as the storage backend for other AWS services.

It's important to note that S3 bucket names must be unique globally across all AWS accounts, so you need to choose a name that hasn't been taken by someone else.

## Identity and Access Management(IAM)

It is a web service provided by Amazon Web Services (AWS) that helps you manage access to your AWS resources securely. IAM allows you to control who can access your resources and what actions they can perform.

**Here are some key concepts and features of IAM in AWS:**

* **Users:** IAM allows you to create and manage IAM users. Users represent individual people or entities (such as applications or services) that interact with AWS resources. Each user is assigned a unique set of security credentials (access key and secret access key) to make API calls or sign in to the AWS Management Console.

<p align="center">
<img src="https://github.com/jijinmichael/S3-and-IAM-user/assets/134680540/412dc925-196b-43f6-a105-042f68ba770f"></p>

* **Roles:** IAM roles are similar to users but are meant for applications or services running within AWS. Roles provide a set of temporary security credentials that can be assumed by entities such as EC2 instances, Lambda functions, or other AWS services. Roles help applications or services access AWS resources securely without the need to manage long-term access keys.

* **Policies:** IAM policies are JSON documents that define permissions. You can attach policies to users, groups, or roles to specify what actions they can perform on which AWS resources. Policies can be either inline (directly attached to an entity) or managed (created and attached separately).

* **Permissions:** IAM allows fine-grained control over permissions through the use of IAM policies. Permissions can be granted or denied for specific actions (such as creating an S3 bucket or launching an EC2 instance) on specific resources (such as a specific S3 bucket or EC2 instance). IAM policies provide flexibility in defining access controls.

* **Access Keys:** IAM allows users to generate access keys (access key ID and secret access key) for programmatic access to AWS resources. Access keys are used by API calls, SDKs, command-line tools, or other AWS services.

IAM is a fundamental component of AWS security, and it is crucial for managing access and enforcing least privilege principles. By using IAM, you can ensure that only authorized individuals or applications have access to your AWS resources, reducing the risk of unauthorized access or accidental misconfiguration.


Let's have a look over the the S3 and IAM services in aws. 
[Click here](https://github.com/jijinmichael/S3-and-IAM-user/wiki)
