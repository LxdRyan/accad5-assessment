# ACCAD 5 Assessment

## Documentation

Website: https://xa3ma9ttqn.ap-southeast-1.awsapprunner.com/

Github: https://github.com/lxdryan/accad5-assessment

### Steps

Changes pushed to Github will trigger CodePipeline which builds the Docker image and pushes it to ECR which causes AppRunner to pull the image and deploy it.

## Images

![codebuild](images/codebuild.png)

_CodeBuild_

![s3](images/s3.png)

_S3_

![codepipeline](images/codepipeline.png)

_CodePipeline_

![apprunner](images/apprunner.png)

_AppRunner_