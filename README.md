# tfc-workflows-github
This repo demo the integration between HCP Terraform and Github through API-driven workflows. 

1. .github folder: defines the workflows \
2. terraform folder: a Terraform config file - main.tf to create an aws instance.

# Two workflows
1. Terraform Speculative Run (Pull Request Open/Edit Workflow): Workflow to run non-applyable speculative runs in HCP Terraform when a pull request has been opened/modified. There are three Actions included in the workflow: Upload, create-run and plan-output.\
2. Terraform Apply Run (Push to main branch/PR Merge to main Workflow): Workflow to perform an apply run for a given workspace. There are three Actions included in the workflow: Upload, create-run and apply. \

The workflows are copied from the repo: [HCP Terraform Workflows for GitHub repo](https://github.com/hashicorp/tfc-workflows-github) /workflow-templates folder, and replaced the <<INPUT REQUIRED>> with all the customized value. 


# Reference : HCP Terraform Workflows for GitHub
https://github.com/hashicorp/tfc-workflows-github/blob/main/README.md \
https://developer.hashicorp.com/terraform/tutorials/automation/github-actions
