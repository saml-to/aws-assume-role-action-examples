[< Go Back to Examples](https://github.com/saml-to/aws-assume-role-action-examples)

# `multiple-accounts` Example

## Config File

[saml-to.yml](saml-to.yml)

## GitHub Action

[multiple-accounts.yml](.github/workflows/multiple-accounts.yml)

**Note**: We could have used a Matrix for parallel processing, however, this demonstrates using outputs from two different role assumptions in the same job

## Identity Provider in AWS IAM

![Identity Provider in AWS IAM](/images/identity-provider.png)

**Note**: Configuration in the 2nd account is identical!

## IAM Role & Policy

![IAM Role](/images/multi-account-role.png)
![Policy](/images/multi-account-policy.png)

**Note**: Configuration in the 2nd account is identical!

## Trust Relationship

![Trust Relationship](/images/trust-relationship-visual.png)
![Trust Relationship JSON](/images/trust-relationship-json.png)

**Note**: Configuration in the 2nd account is identical!

# Have a question?

[Message us on Gitter](https://gitter.im/saml-to/assume-aws-role-action)
