Root user privileges 
- Root user = account owner
- Has complete access to aws services 
- Do not use the root account for everyday tasks, even administrative tasks
- Root user can change account settings 
- They can view certain tax inboxes 
- Change or cancel aws support plan
- Register as a seller in the reserve instance market place. 
- Configure s3 bucket to enable mfa


IAM Access analyzer 
Used to find out which resources are shared externally.
- S3 buckets
- IAM roles 
- KMS keys
- Lambda Functions and layers 
- SQS queues 
- Secret manager secrets
- Define a zone of trust = Aws Account or AWS Organization 
- Access outside zone of trusts => findings 

- Shared Responsability in AWS
- Sheild: Automatic DDoS protection +24/7 support for advacned 
- WAF: Firewall to filter incoming rtequests based on rules 
- KMS: Encryption keys managed by AWS
- CloudHSM: Hardware encryption wer manage these keys 
- AWS Certificate manager: Provision, manage, and deploy SSL/TLS Certificates 
- Artificat: Get access to compliance reports such a PCI, ISO etc
- Guard duty: Find Malicious behvaior with VPC, DNS and CloudTrial Logs
- Inspector: find softwear vulnerabilities in EC2, ECR images, and Lambda functions 
- Config: Track congif and compliance agaisnt rules 
- Macie: Find sensative data i ns3 buckets 
- CloudTrial: Track Api calss amde by useres with an account 
- AWS Security Hub: gather security fidnings form multiple AWS accounts
- Amazon Detection: finbd the root cause of security issues or suspicious activity 
- Aws Abuse: report AWS resources used for abusive or illegal purposes 
- Root User Privilages: change account settings - close aWS account- Change or cancle your AWS Support plan 


# Machine learning 

## Amazon Rekognition 
- Find objects, people, text, scenes in images and videos using ML
- Facial analyaiss and facial search to do user verification, poeple counbting
- create a database of familiar faces or compare against celebrities 
### use cases
- Labeling 
- content moderation 
- Text detection 
- Face detection 
- face search verification 
- celebrity recognition
- pathing - (for sport analysis)