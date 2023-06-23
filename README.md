# TerraformProject is a simple setup example.

#Notes
- Terraform is an open-source infrastructure as code (IaC) tool developed by HashiCorp.
- It allows you to define and provision infrastructure resources across various cloud providers and services.
- Terraform uses declarative configuration files to describe the desired state of your infrastructure, and it automatically manages the creation, modification, and deletion of resources to achieve that state.

Installation:
- Terraform can be installed on various operating systems, including Linux, macOS, and Windows.
- The installation process involves downloading the Terraform binary for your operating system and adding it to your system's PATH.

Basic Syntax:
- Terraform configuration files are written in HashiCorp Configuration Language (HCL) or, alternatively, JSON.
- The main building block in Terraform is a resource. Resources represent infrastructure components such as virtual machines, networks, storage, etc.
- Resources are defined using a resource block specifying the resource type, name, and configuration parameters.
- Variables can be used to make your configurations more dynamic and reusable.
- Outputs allow you to expose values from your Terraform configuration for reference or use in other systems.

Resource Management:
- Terraform supports a wide range of providers, including popular cloud providers like AWS, Azure, and Google Cloud, as well as other services like Docker, Kubernetes, and more.
- Providers are plugins that interact with the APIs of the respective platforms and services to manage the resources.
- Terraform keeps track of the current state of your infrastructure in a state file, which is typically stored locally or remotely.
- When you apply changes to your configuration, Terraform compares the desired state defined in the configuration with the current state and determines the actions needed to achieve the desired state.

Infrastructure Provisioning:
- To provision infrastructure with Terraform, you define the desired state of your infrastructure in a Terraform configuration file.
- The configuration file specifies the resources, their properties, and any dependencies between them.
- Once the configuration is defined, you run the `terraform init` command to initialize the working directory and download the necessary providers.
- After initialization, you can use the `terraform plan` command to preview the changes Terraform will apply without actually making any changes.
- Finally, you use the `terraform apply` command to apply the changes and provision the infrastructure based on the configuration.

Resource: https://developer.hashicorp.com/terraform
