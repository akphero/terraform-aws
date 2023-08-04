# Terraform AWS Management IaC

This repository is used to manage AWS Infrustructure.

### Installation

Step1. Install [Terraform][terraform-help-url]. It will install terraform with required dependencies. Depending on the flavor or your operating system, a different distribution must be used. For this case, I am using CentOS.

    ```shell
    #Install terraform onto your CentOS box
    sudo yum install -y yum-utils
    sudo yum-config-manager --add-repo https://rpm.releases.hashicorp.com/RHEL/hashicorp.repo
    sudo yum -y install terraform
    ``` 



<!-- MARKDOWN LINKS & IMAGES -->

[terraform-help-url]: https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli  