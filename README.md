# terraform-ssp
It contains all the terraform aws code

# Installation of Terraform

## Download Terraform:
curl -O https://releases.hashicorp.com/terraform/0.11.1/terraform_0.11.1_linux_amd64.zip

Check where to unzip package

## Find out executable path
[root@localhost]# echo $PATH

/sbin:/bin:/usr/sbin:/usr/bin

unzip terraform_0.11.1_linux_amd64.zip -d /usr/bin/

## Verify Installation
[root@localhost ja]# terraform -v

Terraform v0.11.1
