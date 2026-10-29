# Experiment 01: Cloud Account Setup and Services Overview in AWS



## DATE: 29/10/26
## NAME: MADHUMITHA R
## REG NO: 212225230158


## Aim

To create an AWS cloud account, configure secure administrative access, and explore the various services available on the Amazon Web Services (AWS) platform.

## Procedure

### Part 1: Creating an AWS Account

#### Step 1: Visit the AWS Website
- Visit the [AWS Official Website](https://aws.amazon.com/).
- Click **Create an AWS Account**.

#### Step 2: Enter Account Information
- **Email Address:** Enter a valid email address that you can access.
- **Password:** Create a strong password.
- **AWS Account Name:** Enter a suitable name for your account, such as your name or organization name.

#### Step 3: Choose the Account Type
- Select **Personal** or **Professional**, depending on your intended use.
- Enter the required contact information, including your name, address, and phone number.

#### Step 4: Enter Payment Information
- Provide the requested credit or debit card details.
- Review the applicable Free Tier benefits, billing terms, and payment requirements before proceeding.

> **Note:** AWS account registration may require payment information. Free Tier eligibility and usage limits vary by service and account plan. Charges may apply if usage exceeds the applicable free allowances.

#### Step 5: Verify Your Identity
- Enter your phone number.
- Choose the available verification method.
- Enter the verification code to confirm your identity.

#### Step 6: Choose a Support Plan
Choose an appropriate support plan from the available options.

- Basic Support
- Developer Support
- Business Support
- Enterprise Support

For beginners, the Basic Support option is generally sufficient.

#### Step 7: Complete the Sign-Up Process
- Review the information you have entered.
- Complete the account registration process.
- Wait for AWS to activate your account.

#### Step 8: Sign In to the AWS Management Console
- Visit the [AWS Management Console](https://console.aws.amazon.com/).
- Sign in using the appropriate account credentials.
- Explore the AWS Management Console to access the available cloud services.

---

### Part 2: Creating a User with Administrative Access

After creating an AWS account, secure the root user and configure administrative access through AWS IAM Identity Center.

#### Step 1: Secure the Root User
1. Sign in to the [AWS Management Console](https://console.aws.amazon.com/) as the **Root user** using the account owner's email address and password.
2. Enable **Multi-Factor Authentication (MFA)** for the root user to strengthen account security.
3. Avoid using the root user for routine administrative tasks.

#### Step 2: Enable IAM Identity Center
1. Open **IAM Identity Center** from the AWS Management Console.
2. Enable the service by following the setup instructions.
3. Configure the required identity and access settings.

#### Step 3: Create an Administrative User
1. Open IAM Identity Center.
2. Create a user and provide the required information.
3. Assign the user appropriate administrative permissions through the relevant permission set.
4. Assign the user to the AWS account.

> **Security Note:** Administrative access provides extensive permissions. Use it carefully and follow the principle of least privilege whenever possible.

#### Step 4: Sign In as the Administrative User
1. Obtain the AWS access portal sign-in URL provided during IAM Identity Center setup.
2. Open the URL and sign in using the newly created user's credentials.
3. Verify that the user can access the AWS account with the assigned permissions.

---

### Part 3: Overview of AWS Services

1. Sign in to the AWS Management Console.
2. Open the **Services** menu to view the available AWS services.
3. Explore the following major service categories:

| **Service Category** | **Examples** | **Purpose** |
|---|---|---|
| Compute | Amazon EC2, AWS Lambda | Run applications and execute code. |
| Storage | Amazon S3, Amazon EBS | Store files, objects, and application data. |
| Database | Amazon RDS, Amazon DynamoDB | Store and manage structured or NoSQL data. |
| Networking | Amazon VPC, Amazon Route 53 | Configure networks, connectivity, and DNS. |
| Security and Identity | AWS IAM, AWS KMS | Manage access permissions and encryption. |
| Monitoring | Amazon CloudWatch, AWS CloudTrail | Monitor resources and record account activity. |
| Artificial Intelligence | Amazon Bedrock, Amazon SageMaker AI | Build and use AI and machine learning applications. |

4. Observe the purpose and basic functionality of each service.
5. Identify services relevant to cloud computing and cloud security.

## Output

<img width="1920" height="1080" alt="Screenshot 2026-10-15 091425" src="https://github.com/user-attachments/assets/b0bfc77c-3244-4d4d-b759-b82e1e3ac34e" />



## Result

Thus, an AWS cloud account was created, secure administrative access was configured using AWS IAM Identity Center, and the various services available on the AWS platform were explored.

