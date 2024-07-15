# BoA
Under deploy.yml you will have to fill in 
<your-lambda-function-name>: The name you want to give your Lambda function.
<your-account-id>: Your AWS account ID.
<your-role-name>: The name of the IAM role with permissions to run Lambda functions.

Go to Your Repository on GitHub:

Navigate to the repository where you want to add the secrets.
Access the Secrets Settings:

Click on Settings at the top of the repository page.
In the left sidebar, click on Secrets and variables and then Actions.
Add New Secrets:

Click on New repository secret.
Add each of the following secrets:
Name: AWS_ACCESS_KEY_ID
Value: Your AWS Access Key ID.
Name: AWS_SECRET_ACCESS_KEY
Value: Your AWS Secret Access Key.
Name: AWS_REGION
Value: Your AWS Region (e.g., us-east-1).
Name: LAMBDA_FUNCTION_NAME
Value: Your desired Lambda function name.
Name: AWS_ACCOUNT_ID
Value: Your AWS Account ID.
Name: IAM_ROLE_NAME
Value: The name of the IAM role with permissions to run Lambda functions.