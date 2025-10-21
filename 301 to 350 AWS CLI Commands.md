## ☁️ AWS CLI Commands

```bash
301. aws configure                                      # Configure AWS CLI credentials
302. aws s3 ls                                          # List S3 buckets
303. aws s3 cp file.txt s3://mybucket/                  # Copy file to S3
304. aws s3 sync . s3://mybucket/                       # Sync local files to S3
305. aws s3 rm s3://mybucket/file.txt                   # Delete file from S3
306. aws ec2 describe-instances                         # List EC2 instances
307. aws ec2 start-instances --instance-ids i-1234567890  # Start EC2 instance
308. aws ec2 stop-instances --instance-ids i-1234567890   # Stop EC2 instance
309. aws ec2 terminate-instances --instance-ids i-1234567890  # Terminate EC2 instance
310. aws ec2 create-key-pair --key-name MyKeyPair       # Create a new key pair
311. aws ec2 describe-volumes                           # List EBS volumes
312. aws ec2 create-volume --size 10 --region us-east-1 # Create an EBS volume
313. aws ec2 attach-volume --volume-id vol-12345 --instance-id i-12345 --device /dev/sdf  # Attach volume
314. aws ec2 describe-security-groups                   # List security groups
315. aws lambda list-functions                          # List Lambda functions
316. aws lambda invoke --function-name my_lambda output.json  # Invoke a Lambda function
317. aws eks update-kubeconfig --name cluster_name      # Configure kubectl for EKS
318. aws rds describe-db-instances                      # List RDS instances
319. aws rds stop-db-instance --db-instance-identifier mydb  # Stop RDS instance
320. aws rds start-db-instance --db-instance-identifier mydb  # Start RDS instance
321. aws ec2 create-snapshot --volume-id vol-12345      # Create EBS snapshot
322. aws ec2 describe-snapshots                         # List EBS snapshots
323. aws cloudwatch describe-alarms                     # List CloudWatch alarms
324. aws ssm send-command --document-name AWS-RunShellScript --targets "Key=instanceIds,Values=i-12345" --parameters commands="df -h"  # Run command on EC2
325. aws iam list-users                                 # List IAM users
326. aws iam list-roles                                 # List IAM roles
327. aws route53 list-hosted-zones                      # List Route 53 hosted zones
328. aws route53 create-hosted-zone --name example.com  # Create a Route 53 hosted zone
329. aws cloudformation list-stacks                     # List CloudFormation stacks
330. aws cloudformation create-stack --stack-name my-stack --template-body file://template.json  # Create a stack
331. aws cloudformation delete-stack --stack-name my-stack  # Delete a stack
332. aws ecr get-login-password --region us-east-1 | docker login --username AWS --password-stdin account_id.dkr.ecr.us-east-1.amazonaws.com  # Login to ECR
333. aws ecr create-repository --repository-name myrepo # Create an ECR repository
334. aws ecr list-repositories                          # List ECR repositories
335. aws dynamodb list-tables                           # List DynamoDB tables
336. aws dynamodb describe-table --table-name mytable   # Describe a DynamoDB table
337. aws dynamodb put-item --table-name mytable --item '{"id": {"S": "123"}, "name": {"S": "Test"}}'  # Insert item into DynamoDB
338. aws sns list-topics                                # List SNS topics
339. aws sns publish --topic-arn arn:aws:sns:us-east-1:123456789012:MyTopic --message "Hello"  # Send SNS message
340. aws sqs list-queues                                # List SQS queues
341. aws sqs send-message --queue-url https://sqs.us-east-1.amazonaws.com/123456789012/MyQueue --message-body "Test message"  # Send message to SQS
342. aws sqs receive-message --queue-url https://sqs.us-east-1.amazonaws.com/123456789012/MyQueue  # Receive SQS message
343. aws kms list-keys                                  # List KMS keys
344. aws kms encrypt --key-id key-id --plaintext "Hello"  # Encrypt text using KMS
345. aws kms decrypt --ciphertext-blob fileb://encrypted.txt  # Decrypt KMS ciphertext
346. aws ec2 describe-key-pairs                         # List EC2 key pairs
347. aws ec2 delete-key-pair --key-name MyKeyPair       # Delete a key pair
348. aws s3 mb s3://my-new-bucket                       # Create a new S3 bucket
349. aws s3 rb s3://my-new-bucket --force               # Delete an S3 bucket
350. aws cloudfront list-distributions                  # List CloudFront distributions
```
