# General information
- Lab + book environment
https://us-east-1.mango.aws.training/class/kK9sQwVqnhwp1WHDoWTRdy
- Evaluation<br>
You should have received an email with a feedback link. If not:<br>
Go to aws.training  and sign in.<br>
After all the prompts go to My Account --> Transcript (top right)<br>
Go to the Archived Tab, and click on the "Evaluate" button and fill the eval form.

# Additional study resources
- Exam information page, with 10 sample questions<br>https://aws.amazon.com/certification/certified-developer-associate/
- Skill builder, with a lot of training and exam prep questions<br>https://explore.skillbuilder.aws/learn
- Measure up, good exam simulation<br>https://www.measureup.com/aws-practice-test-dva-c01-aws-certified-developer-associate.html
- Whizlabs<br>https://www.whizlabs.com/aws-developer-associate/
- A cloud guru<br>https://acloudguru.com/

# My contact details
- Email<br>renatoalmeidamartins@gmail.com
- Linkedin<br>https://www.linkedin.com/in/renatodealmeidamartins/

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
- S3 Select<br>https://docs.aws.amazon.com/AmazonS3/latest/userguide/selecting-content-from-objects.html

# Day 2 links
- Policy generator<br>https://awspolicygen.s3.amazonaws.com/policygen.html
- Sample S3 bucket policies<br>https://docs.aws.amazon.com/AmazonS3/latest/userguide/example-bucket-policies.html
- DynamoDB paper<br>https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf
- Aurora storage basics (2016)<br>https://aws.amazon.com/blogs/database/introducing-the-aurora-storage-engine/
- Aurora storage reliability<br>https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/Aurora.Overview.StorageReliability.html
- Aurora serverless deep dive<br>https://www.youtube.com/watch?v=_2o7vVAxst0
- DynamoDB Fine Grained Access control<br>https://aws.amazon.com/blogs/aws/fine-grained-access-control-for-amazon-dynamodb/
- DynamoDB best practices<br>https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/best-practices.html
- Choosing the right dynamodb partition key<br>https://aws.amazon.com/blogs/database/choosing-the-right-dynamodb-partition-key/
- Fundamentals of DynamoDB design<br>https://www.youtube.com/watch?v=KYy8X8t4MB8
- DyanmoDB advanced design<br>https://www.youtube.com/watch?v=xfxBhvGpoa0
- DynamoDB adapative capacity is instant<br>https://aws.amazon.com/about-aws/whats-new/2019/05/amazon-dynamodb-adaptive-capacity-is-now-instant/
- DynamoDB burst capacity<br>https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/bp-partition-key-design.html#bp-partition-key-throughput-bursting
- DynamoDB local<br>https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/DynamoDBLocal.html
- NoSQL workbench<br>https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/workbench.settingup.html
- Handling errors in DynamoDB<br>https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Programming.Errors.html
- Parallel scan concept in DynamoDB<br>https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Scan.html#Scan.ParallelScan
- DynamoDB Mapper, Java wrapper that takes care of parallel scans<br>https://aws.amazon.com/blogs/aws/amazon-dynamodb-parallel-scans-and-other-good-news/
- Methods in the DynamoDB mapper class<br>https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/DynamoDBMapper.Methods.html
- Developing using DynamoDB DAX<br>https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/DAX.client.html
- Serverless musical parody<br>https://www.youtube.com/watch?v=zMua0cuhFnc
- Best practices for lambda functions<br>https://docs.aws.amazon.com/lambda/latest/dg/best-practices.html
- Deplooy Lambda functions in containers<br>https://docs.aws.amazon.com/prescriptive-guidance/latest/patterns/deploy-lambda-functions-with-container-images.html
- Eventbridge partner integration<br>https://aws.amazon.com/blogs/aws/amazon-eventbridge-event-driven-aws-integration-for-your-saas-applications/
- Lambda HTTP endpoints<br>https://aws.amazon.com/blogs/aws/announcing-aws-lambda-function-urls-built-in-https-endpoints-for-single-function-microservices/

# Day 3 links
- Velocity conference video that is one of the first DevOps a-ha moments<br>https://www.youtube.com/watch?v=LdOe18KhtT4&t=941s
- The phoenix project<br>https://www.amazon.com/The-Phoenix-Project-audiobook/
- The unicorn project<br>https://www.amazon.com/dp/B0812C82T9
- The devops handbook<br>https://www.amazon.com/DevOps-Handbook-Second-World-Class-Organizations/
- The state of devops report<br>https://media.webteam.puppet.com/uploads/2021/07/Puppet-State-of-DevOps-Report-2021.pdf
- Accelerate book<br>https://www.amazon.com/Accelerate-Building-Performing-Technology-Organizations
- Strangler fig pattern<br>https://martinfowler.com/bliki/StranglerFigApplication.html
- Breaking a monolith into microservices<br>https://aws.amazon.com/getting-started/hands-on/break-monolith-app-microservices-ecs-docker-ec2/
- Step Functions state language<br>https://docs.aws.amazon.com/step-functions/latest/dg/supported-services-awssdk.html
- 12 factor app, good principles for modern applications<br>https://12factor.net/
- Step function patters for short and long running workflows<br>https://aws.amazon.com/blogs/mobile/invoking-aws-step-functions-short-and-long-running-workflows-from-aws-appsync/ 
- "There's no place like production", if you are not deploying in production, you are just cheating yourself<br>https://imwrightshardcode.com/2010/12/theres-no-place-like-production/
- Code Build docker images<br>https://docs.aws.amazon.com/codebuild/latest/userguide/build-env-ref-available.html
- SAM CLI repo<br>https://github.com/aws/aws-sam-cli
- SAM repo<br>https://github.com/aws/serverless-application-model
- SAM app repo<br>https://serverlessrepo.aws.amazon.com/applications
- SAM samples GitHub repo<br>https://github.com/aws/aws-sam-cli-app-templates
- Serverless, a paid-for framework similar to SAM<br>https://www.serverless.com/framework/
- CDK, offering a way to create any AWS resource in high-level code<br>https://docs.aws.amazon.com/cdk/v2/guide/constructs.html
- CDK workshop, with walthroughs in several languages<br>https://cdkworkshop.com/
- Custom identity provider<br>https://docs.aws.amazon.com/cognito/latest/developerguide/developer-authenticated-identities.html
- CloudWatch anomaly detection announcement<br>https://aws.amazon.com/about-aws/whats-new/2019/07/introducing-amazon-cloudwatch-anomaly-detection-now-in-preview/
- CloudWatch agent<br>https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/install-CloudWatch-Agent-on-EC2-Instance.html
