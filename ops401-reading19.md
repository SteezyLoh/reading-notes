# Ops Reading 19
## Cloud Detective Controls

**1. What are some of the IoCs that GuardDuty can detect?**
- Some IoC's that GuardDuty can detect arethreat intelligence feeds, such as lists of malicious IP addresses and domains, and machine learning to identify unexpected, potentially unauthorized, and malicious activity within your AWS environment. It also monitors service that analyzes and processes Foundational data sources, such as AWS CloudTrail management events, AWS CloudTrail event logs, VPC flow logs (from Amazon EC2 instances), and DNS logs

**2. What are some of the data sources which GuardDuty can use?**
- Kubernetes audit logs, RDS login activity, S3 logs, EBS volumes, Runtime monitoring, and Lambda network activity logs. 


**3. How does GuardDuty use access behavior to spot potential malicious activity?**
-  GuardDuty informs you of the status of your AWS environment by producing security findings that you can view in the GuardDuty console or through Amazon EventBridge. GuardDuty also provides support for you to export your findings to an Amazon Simple Storage Service (S3) bucket, and integrate with other services such as AWS Security Hub and Detective.

Resources : https://docs.aws.amazon.com/guardduty/latest/ug/what-is-guardduty.html