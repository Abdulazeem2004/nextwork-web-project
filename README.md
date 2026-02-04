# Java Web App Deployment with AWS CI/CD

Welcome to this project combining Java web application development with modern AWS-based CI/CD practices. This repository documents my hands-on journey building, versioning, and preparing a Java web app for automated deployment in the cloud.

<br>

## Table of Contents
- [Introduction](#introduction)
- [Technologies](#technologies)
- [Setup](#setup)
- [Contact](#contact)
- [Conclusion](#conclusion)

<br>

## Introduction

This project serves as an introduction to building, managing, and deploying a Java-based web application using Amazon Web Services, with a strong focus on CI/CD principles.

The web application itself is simple, but the real value of this project lies in the **deployment pipeline** built around it. While the CI/CD process is invisible to end users, it plays a critical role by automating code validation, builds, and deployments. This reduces human error, improves reliability, and ensures consistent releases.

Through this project, I’m learning how professional teams move from manual deployments to **automated, repeatable, and scalable workflows** using cloud-native tools.

<br>

## Technologies

Here’s what I’m using for this project and why each tool matters:

- **Amazon EC2**  
  The Java web application is developed and hosted on Amazon EC2 instances. This allows the entire development and deployment workflow to run in the cloud, closely mimicking real-world production environments.

- **VS Code (Remote SSH)**  
  Visual Studio Code is used as my development environment, connected directly to the EC2 instance via SSH. This setup allows me to edit files, manage folders, and run commands on the remote server as if it were a local machine.

- **Git & GitHub**  
  Git is used for version control, while GitHub hosts the remote repository. This enables change tracking, collaboration readiness, and integration with CI/CD tools.

- **[COMING SOON] AWS CodeArtifact**  
  CodeArtifact will be used to store build artifacts and manage Java dependencies securely. This helps improve availability and speeds up builds by centralizing dependencies.

- **[COMING SOON] AWS CodeBuild**  
  CodeBuild will automate the build process by compiling the Java source code, running tests, and producing deployable artifacts without manual intervention.

- **[COMING SOON] AWS CodeDeploy**  
  CodeDeploy will handle application deployment across EC2 instances, ensuring updates are delivered reliably with minimal downtime.

- **[COMING SOON] AWS CodePipeline**  
  CodePipeline will connect GitHub, CodeBuild, and CodeDeploy into a single automated CI/CD workflow, enabling continuous integration and continuous delivery from code commit to production.

<br>

## Setup

To get this project up and running locally or in a cloud environment, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/nextwork-web-project.git
    ```

2. Navigate to the project directory:
    ```bash
    cd nextwork-web-project
    ```

3. Install dependencies and build the project:
    ```bash
    mvn install
    ```

> Note: In this project, most development is done directly on an EC2 instance using VS Code Remote SSH to better simulate a real cloud-based workflow.

<br>

## Contact

If you have any questions, feedback, or suggestions about this project, feel free to reach out:

**Abdulazeem**  
📧 [badmusazeem05@gmail.com](mailto:badmusazeem05@gmail.com)

<br>

## Conclusion

Thank you for exploring this project!

This repository represents my growing understanding of Java web applications, cloud infrastructure, and CI/CD automation using AWS. As the project evolves, I’ll continue adding more automation, improving deployment reliability, and refining best practices that can be applied to real-world DevOps environments.

A big shoutout to **[NextWork](https://learn.nextwork.org/app)** for their clear project guides and learning support.  
👉 You can start this DevOps series project too by clicking here:  
[https://learn.nextwork.org/projects/aws-devops-vscode?track=high](https://learn.nextwork.org/projects/aws-devops-vscode?track=high)

