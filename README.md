* To deploy, follow the following commands:

```
aws cloudformation deploy \
--template-file ./cloudformation.yml \
--stack-name apollo-server-lambda-nodejs \
--parameter-overrides BucketName=labhijeet-lambda-deploy-bucket Version=latest \
--capabilities CAPABILITY_IAM
```

