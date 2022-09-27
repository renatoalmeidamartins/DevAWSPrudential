# General information
- Lab + book environment
https://us-east-1.mango.aws.training/class/kK9sQwVqnhwp1WHDoWTRdy

# Day 1 links

- AWS developer tools<br>https://aws.amazon.com/developer/tools/
- Signing requests for the AWS REST API<br>https://docs.aws.amazon.com/AmazonS3/latest/API/sig-v4-authenticating-requests.html
- Setting retries, errors and timeouts in the SDK
  - General considerations about timeouts and retries<br>https://aws.amazon.com/builders-library/timeouts-retries-and-backoff-with-jitter/
   - .Net<br>https://docs.aws.amazon.com/sdk-for-net/v3/developer-guide/retries-timeouts.html
   - Java blog announcement about retries and timeouts<br>https://aws.amazon.com/blogs/developer/introducing-retry-throttling/
   - specific config for Java SDK<br>https://docs.aws.amazon.com/sdk-for-java/v1/developer-guide/section-client-configuration.html
- Pagination support with the Java SDK<br>https://docs.aws.amazon.com/sdk-for-java/latest/developer-guide/pagination.html
- Waiters (available for several services)
  - DynamoDB<br>https://docs.aws.amazon.com/cli/latest/reference/dynamodb/wait/
  - S3<br>https://docs.aws.amazon.com/cli/latest/reference/s3/wait/
  - EC2<br>https://docs.aws.amazon.com/cli/latest/reference/ec2/wait/
  - There are several others, just replace the service name in the URL and you will see
- SDK Error logging<br>https://docs.aws.amazon.com/sdk-for-java/v1/developer-guide/java-dg-logging.html
- Named profiles in the CLI<br>https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-profiles.html
- There are plenty of browser extensions to manage roles. A popular one is the AWS Extend Switch Roles. Link for chrome below:<br>https://chrome.google.com/webstore/detail/aws-extend-switch-roles/jpmkfafbacpgapdghgdpembnojdlgkdl
- Priority order for credential usage when connecting to AWS<br>https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-quickstart.html#cli-configure-quickstart-precedence
- EBS volume types<br>https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ebs-volume-types.html
- EBS multi-attach<br>https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ebs-volumes-multi.html
- S3 storage classes compared<br>https://aws.amazon.com/s3/storage-classes/
- S3 pricing<br>https://aws.amazon.com/s3/pricing/?nc=sn&loc=4
- S3 helpers for multipart upload<br>
  - Java<br>https://docs.aws.amazon.com/AWSJavaSDK/latest/javadoc/com/amazonaws/services/s3/transfer/TransferManager.html
  - .Net<br>https://docs.aws.amazon.com/sdkfornet/v3/apidocs/items/S3/TTransferUtility.html
