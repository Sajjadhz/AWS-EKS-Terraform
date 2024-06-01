# AWS-EKS-Terraform

### 1. Installation:

#### Installing AWS CLI:
- Install AWS CLI on your local machine by following the installation instructions provided in the [AWS CLI User Guide](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html).

#### Configuration:
- After installation, configure AWS CLI by running `aws configure` command.
- Provide your AWS Access Key ID, Secret Access Key, default region, and output format (JSON, text, or table) when prompted.


### 2. Cloning the Repository

To clone this repository, use the following command:

#### Using HTTPS

```sh
git clone https://github.com/Sajjadhz/AWS-EKS-Terraform.git
```

### 2. Creating EKS cluster using Terraform

To create the EKS Cluster, use the following commands:

```sh
cd AWS-EKS-Terraform/terraform
terraform init
terraform plan
terraform apply
```