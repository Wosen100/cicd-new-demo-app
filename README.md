# cicd-new-demo-app
# CI/CD Pipeline Project with AWS Elastic Beanstalk, CodeBuild, and CodePipeline
# Overview

This project demonstrates a complete CI/CD (Continuous Integration and Continuous Deployment) workflow built using AWS services. The goal was to automate the process of building, testing, and deploying an application with high efficiency and reliability.

The deployment environment is powered by AWS Elastic Beanstalk, while AWS CodeBuild handles the build process and AWS CodePipeline orchestrates the workflow. Artifacts generated during the build process are stored in Amazon S3 for secure and scalable storage.

# Architecture and Workflow

# Source Stage

Code changes are committed and pushed to the GitHub repository.

CodePipeline automatically detects the changes and triggers the pipeline.

# Build Stage

CodeBuild retrieves the source code and runs the build commands defined in the buildspec.yml file.

The build artifacts (compiled code, dependencies, etc.) are stored in Amazon S3.

# Deploy Stage

Elastic Beanstalk automatically deploys the latest build from S3.

The application is hosted in a scalable environment with load balancing and health monitoring.

# Automation

The entire process (from code commit to deployment) runs automatically, ensuring fast, consistent, and error-free releases.

# Technologies Used

AWS Elastic Beanstalk – Application hosting and deployment

AWS CodePipeline – Continuous integration and delivery automation

AWS CodeBuild – Build and test automation

Amazon S3 – Artifact and static file storage

GitHub – Source control and version management

# Project Screenshots

(Add your attached images here once uploaded — for example)

![Pipeline Overview](images/pipeline-overview.png)
![CodeBuild Logs](images/codebuild-logs.png)
![Elastic Beanstalk Dashboard](images/elasticbeanstalk-dashboard.png)

# Key Features

Fully automated CI/CD pipeline from GitHub to AWS

Scalable and reliable deployment with Elastic Beanstalk

Build automation using CodeBuild with buildspec.yml

Centralized artifact management with Amazon S3

Real-time monitoring and logs for build and deployment status

# Future Improvements

Integrate unit and integration testing during the build stage

Add notification triggers using Amazon SNS

Implement blue/green deployment strategies for zero-downtime updates

# Author

Wosen Negussie
📍 Fresno, CA
💼 Tech Industry Professional | Cloud & DevOps Enthusiast

