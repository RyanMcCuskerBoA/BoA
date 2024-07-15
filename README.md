# BoA

## Configuration

### Adding Secrets to Your Repository

#### Go to Your Repository on GitHub

1. Navigate to the repository where you want to add the secrets.
2. Access the Secrets Settings:
   - Click on `Settings` at the top of the repository page.
   - In the left sidebar, click on `Secrets and variables` and then `Actions`.

#### Add New Secrets

Click on `New repository secret` and add each of the following secrets:

- **Name:** `AWS_ACCESS_KEY_ID`
  - **Value:** Your AWS Access Key ID.
- **Name:** `AWS_SECRET_ACCESS_KEY`
  - **Value:** Your AWS Secret Access Key.
- **Name:** `AWS_REGION`
  - **Value:** Your AWS Region (e.g., `us-east-1`).
- **Name:** `LAMBDA_FUNCTION_NAME`
  - **Value:** Your desired Lambda function name.
- **Name:** `AWS_ACCOUNT_ID`
  - **Value:** Your AWS Account ID.
- **Name:** `IAM_ROLE_NAME`
  - **Value:** The name of the IAM role with permissions to run Lambda functions.
