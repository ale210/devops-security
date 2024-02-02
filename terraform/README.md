<!-- BEGIN_TF_DOCS -->
# Overview
This module declares all of the resources necessary to create AWS IAM related resources.

# Terraform Directory

## Modules

| Name | Source | Version |
|------|--------|---------|
| <a name="module_iam_read_only_group"></a> [iam\_read\_only\_group](#module\_iam\_read\_only\_group) | ./modules/aws-groups | n/a |
| <a name="module_iam_user_gwenstacy"></a> [iam\_user\_gwenstacy](#module\_iam\_user\_gwenstacy) | ./modules/aws-users | n/a |






To automatically update this documentation, install terraform-docs on your local machine run the following: 
    cd <directory of README location to update>
    terraform-docs -c .terraform.docs.yml . 

# Directory Structure
Terraform directory structure

- 📁 [terraform](https://github.com/hackforla/ops-security/tree/cb/example/terraform)
  - 📁  [aws-custom-policies](https://github.com/hackforla/ops-security/tree/cb/example/terraform/aws-custom-policies) - JSON configurations for customer-managed policies (AWS-managed policies are referenced by ARN and not needed here)
      - 📁 [existing-policies](https://github.com/hackforla/ops-security/tree/cb/example/terraform/aws-custom-policies/existing-policies) - a few of our current policy configurations for reference
  - 📁 [modules](https://github.com/hackforla/ops-security/tree/cb/example/terraform/modules) - reusable Terraform configurations
  - 📄 [aws-custom-policies.tf](https://github.com/hackforla/ops-security/tree/cb/example/terraform/modules/aws-groups) - maintain custom policies here
  - 📄 [aws-groups.tf](https://github.com/hackforla/ops-security/tree/cb/example/terraform/modules/aws-groups) - maintain groups here
  - 📄 [aws-users.tf](https://github.com/hackforla/ops-security/tree/cb/example/terraform/modules/aws-users) - maintain users here
    
<!-- END_TF_DOCS -->    