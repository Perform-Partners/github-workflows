# github-workflows
A collection of reusable Github Action workflows

## Structure
* All workflows have to be stored as yaml files under `.github/workflows`, no other directories are allowed/supported by Github Actions.
* File names in the format of `<technology>-<workflow context>.yml`, e.g. 
    * `terraform-main.yml` for a Terraform pipeline that runs on `main` branch events 
    * `docker-pr.yml` for a Docker image repo pipeline that runs on pull request events.
    
