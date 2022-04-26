# github-workflows
A collection of reusable Github Action workflows

## Structure
* All workflows have to be stored as yaml files under `.github/workflows`, no other directories are allowed/supported by Github Actions.
* File names in the format of `<technology>-<workflow context>.yml`, e.g. 
    * `terraform-release.yml` for a Terraform pipeline that runs when releasing - usually when merging to `main` branch.
    * `terraform-module-pr.yml` for a Terraform module pipeline that runs on pull requests.
    * `docker-pr.yml` for a Docker image repo pipeline that runs on pull request events.
    * `workflows-release.yml` contains release actions that run in this very repo.
    
