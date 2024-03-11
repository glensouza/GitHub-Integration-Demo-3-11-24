# GitHub Integration Demo 3/11/24

This is a demo on how to integrate GitHub with Azure DevOps. This is a useful tool for developers who want to use GitHub for source control and Azure DevOps for CI/CD pipelines. This demo will cover the following topics:

1. [What is GitHub?](#what-is-github)
1. [What is Azure DevOps?](#what-is-azure-devops)
1. [Why integrate GitHub with Azure DevOps?](#why-integrate-github-with-azure-devops)
1. [Resources](#resources)

## What is GitHub?

GitHub is a web-based platform that uses Git for version control. GitHub provides a variety of features such as source code management, issue tracking, project management, workflow with GitHub Actions, and wikis for every project.

## What is Azure DevOps?

Azure DevOps is a set of development tools used for software development. It includes source control, work item tracking, continuous integration (Pipeline), and continuous deployment (Release).

## Why integrate GitHub with Azure DevOps?

Integrating GitHub with Azure DevOps allows developers that are currently using Azure DevOps deeply in their project management and development lifecycle, but are interested in exploring GitHub features. When you're not ready to fully transition to GitHub, but are still interested in testing out features, you integrate them together. This allows developers to take advantage of the best features of both platforms and use them together to manage, build, test, and deploy their applications. This integration provides a seamless experience for developers and allows them to use the best tools for their projects.

## Resources

- [GitHub](https://github.com)
- [Azure DevOps](https://azure.microsoft.com/en-us/services/devops)
- [Integrate GitHub with Azure DevOps](https://learn.microsoft.com/en-us/azure/devops/cross-service/github-integration)
- [Azure DevOps Documentation](https://docs.microsoft.com/en-us/azure/devops)
- [GitHub Documentation](https://docs.github.com/en)
- [Azure DevOps Boards Link to from Github](https://learn.microsoft.com/en-us/azure/devops/boards/github/link-to-from-github?view=azure-devops)
- [Azure Devops Project Used on This Demo](https://dev.azure.com/glenster75/GitHub-Integration-Demo-3-11-24)
- [Azure Boards GitHub Marketplace](https://github.com/marketplace/azure-boards)

## Demo

1. Create a new repository in GitHub
1. Create a new project in Azure DevOps
1. Integrate GitHub with Azure DevOps
1. Create a new pipeline in Azure DevOps
1. Trigger the pipeline by making a change in the GitHub repository
1. Verify that the pipeline runs successfully
1. Create a new classic pipeline in Azure DevOps
1. Trigger the classic pipeline by making a change in the GitHub repository
1. Verify that the classic pipeline runs successfully
1. Add a bug in Azure Boards
1. Push code in another branch related to the bug to GitHub
1. Verify that the bug is linked to the commit
1. Pull request in GitHub with "Fixes" to GitHub
1. Verify that the pull request is linked to the bug
