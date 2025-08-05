Jenkins CI/CD Pipeline with Docker

Overview

This task of working demonstrates a basic Continuous Integration and Continuous Deployment (CI/CD) pipeline using Jenkins and Docker. It automates the process of building, testing, and deploying a simple Node.js application inside a Docker container.

Tools Used

-Jenkins: Automation server to create and run the CI/CD pipeline
-Docker: To containerize and deploy the application
-GitHub: To store the source code and Jenkinsfile

Pipeline Stages

1.Build: Builds a Docker image of the Node.js app using the `Dockerfile`.
2.Test: Performs a basic test to ensure the app runs.
3.Deploy: Runs the Docker container from the built image.

Objective

To automate application deployment using a Jenkins pipeline triggered by code changes.

Files Included

- `app.js` – Sample Node.js script
- `Dockerfile` – Instructions to build the Docker image
- `Jenkinsfile` – Pipeline script defining build, test, deploy stages

