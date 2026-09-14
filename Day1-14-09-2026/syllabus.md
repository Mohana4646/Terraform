# Terraform – Complete Infrastructure as Code (IaC) Syllabus

## Module 1: Introduction to Infrastructure as Code (IaC)

* Challenges of Traditional Infrastructure Management
* What is Infrastructure as Code (IaC)?
* Why Terraform?
* Benefits and Use Cases of Terraform
* Terraform vs Configuration Management Tools

  * Ansible
  * Chef
  * Puppet
* Introduction to HCL (HashiCorp Configuration Language)

## Module 2: Terraform Installation & Environment Setup

* Installing Terraform on:

  * Linux
  * Windows
  * macOS
* Configuring Terraform Environment
* Terraform CLI Commands
* Terraform Version Management
* Terraform vs AWS CloudFormation vs Pulumi

## Module 3: Terraform Core Concepts & Blocks

* Understanding Terraform Configuration Files
* `terraform` Block
* `provider` Block
* AWS Provider Configuration
* `resource` Block
* `variable` Block
* `output` Block
* `locals` Block
* `data` Block
* `module` Block
* Resource Referencing and Dependencies

## Module 4: Working with Terraform Resources

* Resource Syntax and Configuration
* Resource Arguments and Attributes
* Resource Dependencies
* Terraform Meta-Arguments:

  * `count`
  * `for_each`
  * `depends_on`
  * `lifecycle`
* Resource Creation, Modification, and Deletion

## Module 5: Variables, Locals & Outputs

* Understanding Input Variables
* Passing Variables through:

  * CLI
  * `.tfvars`
  * `auto.tfvars`
  * Environment Variables
* Variable Types:

  * String
  * Number
  * Boolean
  * List
  * Map
  * Set
  * Object
  * Tuple
* Complex Variables
* Variable Validation
* Sensitive Variables and Secure Data Handling
* Local Values
* Output Values

## Module 6: Terraform Data Sources

* Understanding Data Sources
* Using `data` Blocks
* Referencing Existing Infrastructure
* AWS Data Sources:

  * AMI
  * VPC
  * Subnets
  * Availability Zones
  * Security Groups
* Data Sources vs Resources

## Module 7: Terraform Expressions & Functions

* Terraform Expressions
* Built-in Functions:

  * `lookup`
  * `join`
  * `length`
  * `merge`
  * `concat`
  * `split`
  * `flatten`
* Conditional Expressions
* For Expressions
* Dynamic Expressions
* Iteration and Collection Handling

## Module 8: Provisioners & Null Resources

* Understanding Terraform Provisioners
* `local-exec`
* `remote-exec`
* Provisioner Use Cases and Limitations
* Introduction to `null_resource`
* Using Triggers with `null_resource`
* Best Practices and Alternatives

## Module 9: Dynamic Blocks

* What are Dynamic Blocks?
* Dynamic Block Syntax
* Using `for_each` with Dynamic Blocks
* Practical Use Cases
* Dynamic Security Group and Network Configuration Examples

## Module 10: Terraform State Management

* Understanding Terraform State
* `terraform.tfstate`
* State Locking
* Local vs Remote State
* Remote Backends
* AWS S3 Backend
* State Locking with AWS
* State Management Commands:

  * `terraform state list`
  * `terraform state show`
  * `terraform state rm`
  * `terraform state mv`
* State File Best Practices
* State Security and Backup

## Module 11: Terraform Modules

* What are Terraform Modules?
* Root vs Child Modules
* Creating Local Modules
* Calling and Using Modules
* Passing Variables to Modules
* Module Outputs
* Using Modules from the Terraform Registry
* Module Versioning
* Module Reusability
* Terraform Module Best Practices

## Module 12: Terraform Workspaces

* Understanding Terraform Workspaces
* Default vs Named Workspaces
* Creating and Managing Workspaces
* Workspace Isolation
* Workspace-Specific Variables and State
* Workspace Use Cases and Limitations

## Module 13: Terraform Cloud – Introduction

* Introduction to Terraform Cloud
* Terraform Cloud vs Terraform CLI
* Remote State Management
* Remote Runs
* VCS Integration
* Connecting GitHub with Terraform Cloud
* Basic Team and Collaboration Concepts

## Module 14: Terraform CI/CD Integration

* Terraform in CI/CD Pipelines
* GitHub Actions + Terraform
* Jenkins + Terraform
* Terraform Workflow:

  * `init`
  * `validate`
  * `plan`
  * `apply`
* Pull Request-Based Terraform Workflow
* Approval and Manual Intervention
* Secure Credential Management
* End-to-End Infrastructure Deployment Project

## Module 15: Hands-on Practice & Interview Preparation

* Common Terraform Errors
* Debugging and Troubleshooting
* Terraform Best Practices
* Real-Time Infrastructure Scenarios
* Production-Oriented Terraform Use Cases
* Scenario-Based Interview Questions
* 20+ Terraform Interview Questions with Answers
* Terraform Troubleshooting Scenarios
* End-to-End Real-Time Project Discussion
