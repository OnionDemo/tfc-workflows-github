# tfc-workflows-github
This repo demo the integration between HCP Terraform and Github through API-driven workflows. 

.github folder: defines the workflows \
actions folder: defines the Github actions. \
We will also create a Terraform config file - main.tf to create an aws instance.

# Two workflows
Terraform Speculative Run (Pull Request Open/Edit Workflow): Workflow to run non-applyable speculative runs in HCP Terraform when a pull request has been opened/modified. \
Terraform Apply Run (Push to main branch/PR Merge to main Workflow): Workflow to perform an apply run for a given workspace.


# Reference : HCP Terraform Workflows for GitHub
https://github.com/hashicorp/tfc-workflows-github/blob/main/README.md 
