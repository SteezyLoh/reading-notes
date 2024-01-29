# Ops Reading 16
## Cloud Identity and Access Management (IAM) with AWS

These things are important because we can always learn from other or our mistakes

**1. What were the three commands used for the attack?**
- Get Credentials - This was the first command and it obtained security credentials
- List Buckets - The second command use the same security credentials list all files and folders (s3 bucket)
Download Files- The third command download the files what were accessible by the credentials 

**2. What misconfiguration of AWS components allowed the attacker to access sensitive data?**
- The S3 buckets were not exposed to the internet. Stuff with high-risk permissions and very important stuff were compromised without being notice 

**3. What are two of the AWS Governance practices that could have prevented such attack?**
- Review all access path and permissions from human and non human identities 
- Do not allow EC2 instance or autoscaling group to have its own IAM role


# I wish i knew more about who and when they did the attack