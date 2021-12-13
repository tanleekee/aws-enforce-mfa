## Reference from AWS documentation:
https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_examples_aws_my-sec-creds-self-manage.html

1. Create a new policy using the policy code
2. Create a new admin group, attach polic created in step 1
3. Create new IAM user, add to admin group created in step 2
4. IAM user able to logon to AWS console. However user would not be able to perform any task unless enroll MFA
