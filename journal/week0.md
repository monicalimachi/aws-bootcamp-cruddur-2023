# Week 0 — Billing and Architecture

## Recreated Conceptual Diagram on a Napkin
![napkin](https://user-images.githubusercontent.com/12466501/219552681-680c10ab-128e-473a-b521-12ed288d6e88.jpg)

## Recreated Logical Architectual Diagram in Lucid Charts
The LucidChart Link is: https://lucid.app/lucidchart/1b6ba6c7-3b77-441e-8cb8-1b2a6c9fa571/edit?viewport_loc=-25%2C-74%2C2188%2C1614%2C0_0&invitationId=inv_8c7eefed-4408-492b-b0a2-6d426f66735d
![Blank diagram](https://user-images.githubusercontent.com/12466501/219567818-7f730fea-f657-4655-974c-c8fcc6fb38c2.png)

## Configured AWS Account
A new IAM user was created to Admin the account, the account has MFA activated and other security options suggested like API Keys.
Configured Budgets with alerts, it's costing some cents at the moment. I have created three initally but removed one to use the two free alerts
Configured Cost Management
![CostSummary](https://user-images.githubusercontent.com/12466501/227066680-0751b7f4-fa1e-4c48-9c9f-ce6b6af4feb9.jpg)

## Configured AWS CLI
Configured gitpod and included env variables
The Gitpod was configured with AWS API Key to have access to the environment to test AWS Cloud Shell

## Generated AWS Credentials and tested on gitpod.yml
I configured the gitpod with my AWS credentials but for security purposes they were added to the GITPOD ENV variables.
https://github.com/monicalimachi/aws-bootcamp-cruddur-2023/blob/main/.gitpod.yml
