# Multi-Job-Workflow
In this challenge, you will build a GitHub Actions workflow that compiles and runs Go code across multiple operating systems. You’ll also create a final job that performs cross-compilation to generate binaries for multiple platforms.

This hands-on exercise helps you understand multi-job workflows, job dependencies, and cross-platform automation in GitHub Actions.

🔍 Overview

You will complete the following tasks:

Create a new GitHub repository using the Go .gitignore template.

Open the repository in the GitHub Web Editor to add Go source code and workflow files.

Create the main.go file containing your Go program.

Add a multi-job workflow triggered by push events that includes four jobs:

One job each for Ubuntu, Windows, and macOS

A fourth job that runs after all three OS jobs finish, performing cross-compilation

Push your changes to trigger the workflow.

Review the Actions tab to verify that all jobs executed successfully on every platform.

⏱️ Estimated time to complete: 15–20 minutes

📝 Instructions
1. Create a new repository

Go to GitHub and select New repository.

Name the repository (example: multi-job-workflow).

Choose Public or Private visibility.

Select Add .gitignore, then choose the Go template.

Leave remaining settings as default and click Create repository.

2. Open the repository in the GitHub Web Editor

Press . (dot) on your keyboard inside the repository, or

Change the URL from github.com ➝ github.dev
