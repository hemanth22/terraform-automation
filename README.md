# Terraform Automation

A project to demonstrate how to automate terraform workflow with Github Actions.

* Github Actions after creating a pull request
![image]()

* Github Actions after Merging to **main** branch
![image]()

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development purpose.

## Prerequisites

To get started with this project you need a basic knowledge of the following.
```
Version Control (Git)
Terraform
AWS
```

## Automating Terraform with Github Actions

* Create a new workspace on Terraform Cloud.
* Then add `AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY` with their respective values as environment variables in the new Terraform Cloud workspace.
* From your Terraform Cloud User Settings, generate an API token named `GitHub Actions`, then add it to your Github repository as a secret. Name the secret `TF_API_TOKEN`.

* Clone and open your Github repo on your code editor.
* Checkout to a new branch with `git checkout -b <branch-name>`.
* Add your changes with `git add .` and commit the changes with a message using `git commit -m "<commit-message>"`.
* Then push your changes with `git push`.
* Go back to the Github repository and generate a pull request from the new branch. You can view the status of the job through the pull request created, Github Actions page or the Terraform Cloud organization.

## Author

* [Mariam Adedeji](https://github.com/mariehposa)

## Acknowledgments

* Github
* Forem