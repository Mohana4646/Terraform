Module 1: Introduction to Infrastructure as Code (IaC)

Traditional Infrastructure Challenges
What is IaC & Why Terraform?
IaC vs Configuration Management Tools (Ansible, Chef)
Introduction to HCL (HashiCorp Configuration Language)



Module 2: Terraform Installation & Setup

Install Terraform on Linux, Windows, Mac
CLI Commands & Versioning
Terraform vs CloudFormation vs Pulumi
Module 3: Terraform Core Blocks

terraform Block
provider Block (with AWS)
resource Block
variable Block (input, output, locals)
data Block
module Block
referencing resources

Module 4: Working with Resources

Resource Syntax and Arguments
Resource Meta-Arguments:
count
depends_on
for_each
lifecycle


Module 5: Variables & Outputs
Input Variables:
CLI variables
.tfvars and auto.tfvars
Environment variables
Lists, Maps, and Complex Variables
Sensitive Data Handling
Output Values


Module 6: Data Sources
Using data block to reference existing infrastructure
AWS Data Sources (AMI, VPC, Subnets, etc.)



Module 7: Expressions & Functions
Built-in Functions (lookup, join, length, etc.)
Dynamic Expressions
Conditional Expressions and Loops


Module 8: Provisioners & Null Resources
local-exec and remote-exec
Use of null_resource for triggers


Module 9: Dynamic Blocks
Dynamic Blocks Syntax
Use Case Examples


Module 10: Terraform State Management
terraform.tfstate & state.lock
Local vs Remote State
State Backends (S3 with DynamoDB Locking)
State Commands (list, show, rm, mv)


Module 11: Terraform Modules
Create & Use Local Modules
Modules from Terraform Registry
Reusability and Best Practices


Module 12: Workspaces
Default vs Named Workspaces
Workspace Isolation and Management


Module 13: Terraform Cloud (Intro Only)
Terraform Cloud vs CLI
Remote Runs, State Storage, VCS Integration


Module 14: Real-Time CI/CD Integration
Automate Terraform with GitHub Actions
Jenkins + Terraform Pipeline
One End-to-End Infrastructure Use Case


Module 15: Practice & Interview Readiness
Common Errors & Troubleshooting
Real-Time Scenarios
20+ Interview Questions with Solutions
