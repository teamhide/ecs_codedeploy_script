 # AWS ECS CodeDeploy Script

Trigger Codedeploy associated with AWS ECS Blue/Green Deployment

## Usage

You have to change below contents.<br /><br />

*prod/test_appspec.yaml*

`TASK_DEFINITION_ARN_HERE` : Task Definition ARN<br /><br />

*prod/test_deploy.sh*

`BUCKET_NAME_HERE` : S3 Bucket name

`CODEDEPLOY_APPLICATION_NAME_HERE` : CodeDeploy Application Name

`CODEDEPLOY_DEPLOYMENT_GROUP_NAME_HERE` : CodeDeploy Deployment Group Name
