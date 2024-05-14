# Tech 258 - IaC

## What is IaC?
Infrastructure as Code (IaC) is a methodology that allows you to manage and provision resources on the cloud, such as servers, networks and storage, using code. This means defining your infrastructure requirements in a machine-readable format rather than manually configuring each component. These setups are in the form of code so they can be version-controlled, tested and deployed like software.

## Why do we use IaC?
- **Automation**: IaC automates the provisioning and configuration of infrastructure, reducing manual effort, risk of human error and makes our deployments consistent.
- **Scalability**: IaC makes the scaling of infrastructure easy as we can modify the code definitions rather than make manual changes.
- **Version Control**: Our code can be stored in version control systems like Git, allowing for tracking of changes, collaboration or rollbacks.

## How do we use IaC?
There are an array of tools that we can use but they are categorised into two groups, *Orchestration* and *Configuration Management*. On the Orchestration side of things, the most popular tool is Terraform and on the other side it is Ansible. 

These tools allow us to write code that specifies the desired state of our infrastructure. The IaC tool will handle the provisioning and configuration based on these desired conditions.

## Where do we use IaC?
IaC can be used in various scenarios and environments, including:
- **Cloud Environments**: AWS, Azure, GCP
- **On-Premises Data Centers**: Physical or Virtual Servers
- **Containerised Environments**: Kubernetes
- **Disaster Recovery**: Automated infrastructure recovery processes# tech258_iac
