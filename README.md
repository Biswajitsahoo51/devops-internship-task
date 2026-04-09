![CI Pipeline](https://github.com/Biswajitsahoo51/devops-internship-task/actions/workflows/main.yml/badge.svg)
# DevOps CI/CD Internship Task

## Project Overview

This project demonstrates a basic **CI/CD pipeline using GitHub Actions**. The goal of the task was to automate the process of building and testing a Node.js application whenever changes are pushed to the repository.

## Technologies Used

* Node.js
* Docker
* GitHub Actions
* Git
* CI/CD Pipeline

## Project Structure

```
devops-internship-task
│
├── app.js
├── package.json
├── Dockerfile
└── .github
     └── workflows
          └── main.yml
```

## Code Explanation

* **app.js**: A simple Node.js server that runs on port 3000 and displays a message confirming the DevOps task execution.
* **package.json**: Contains project dependencies and configuration for the Node.js application.
* **Dockerfile**: Used to containerize the Node.js application using Docker.
* **main.yml**: Defines the CI/CD pipeline using GitHub Actions.

## CI/CD Pipeline Workflow

The pipeline is automatically triggered when code is pushed to the `main` branch.

The workflow performs the following steps:

1. Checkout the repository code
2. Setup Node.js environment
3. Install project dependencies
4. Run a basic test command
5. Build a Docker image for the application

## Dataset

This project does not require a dataset because it focuses on **DevOps pipeline automation** rather than data processing.

## Outcome

The CI pipeline successfully runs whenever changes are pushed to the repository. The workflow automates the build and test process, demonstrating basic DevOps automation practices.

## Repository Link

https://github.com/Biswajitsahoo51/devops-internship-task
