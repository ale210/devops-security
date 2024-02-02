<!-- BEGIN_TF_DOCS -->
# Policies

This module declares all of the resources necessary to create AWS IAM policies.



## Resources

| Name | Type |
|------|------|
| [aws_iam_policy.custom_policy](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy) | resource |
## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_policies"></a> [policies](#input\_policies) | Map of policy definitions | <pre>map(object({<br>    description = string<br>    filename    = string<br>  }))</pre> | n/a | yes |
## Outputs

| Name | Description |
|------|-------------|
| <a name="output_policy_arns"></a> [policy\_arns](#output\_policy\_arns) | Map of policy names to their ARNs |
## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | n/a |


To automatically update this documentation, install terraform-docs on your local machine run the following: 
    cd <directory of README location to update>
    terraform-docs -c .terraform.docs.yml . 
<!-- END_TF_DOCS -->    