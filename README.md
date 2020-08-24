## Terraform Repo Layout
Using this repo layout, you can have multiple products(apps) and multiple environments of that product and your products can share modules.
This repo uses the ['terra_wrap' command](https://github.com/hal58th/terra_wrap) and is a fully working example that uses AWS.

### Running Terraform
A custom docker container is created to help control the Terraform version and lets you add any software you wish.
You will build and run the docker container by running the command:
```bash
make run
```
If you use an IDE to write your code, you will still have to install Terraform locally.

## Setting up AWS Credentials (If using AWS)
[First you must install the aws cli client.](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2-mac.html)
```
```bash
aws configure --profile (PROFILE-NAME)
```
This will prompt you for your secret access key. [Where to get your secret access key.](https://docs.aws.amazon.com/general/latest/gr/aws-sec-cred-types.html#access-keys-and-secret-access-keys)

