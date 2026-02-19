 **Flask DevOps CI Project**
 
**📌 Project Overview**
This project demonstrates a containerized Python Flask application integrated with an automated CI pipeline using GitHub Actions.

**Dockerized Flask App with GitHub Actions CI** .This project demonstrates an end-to-end CI setup for a Dockerized Python Flask application.
I containerized a simple Flask app using Docker and automated the build process using GitHub Actions so that every push to the repository triggers a Docker image build. 
The goal was to understand containerization, CI workflows, and debugging in a real development environment.

During the process, I faced multiple practical issues. The initial Docker build failed due to a missing requirements.txt file and incorrect project structure. 
I also encountered pip installation warnings and dependency resolution problems. Additionally, my WSL environment had high disk usage, which slowed down builds and required troubleshooting before proceeding.
I debugged the Docker build context, corrected file placement, ensured dependencies were properly defined, and rebuilt the image successfully. 
After that, I created a GitHub Actions workflow inside .github/workflows/ to automate Docker builds on every push. Once configured correctly, the CI pipeline ran successfully and 
showed a green status, confirming a reproducible and automated build process.

This project strengthened my understanding of Docker layers, dependency management, Git workflows, and CI automation. 
More importantly, it helped me develop structured debugging skills across multiple layers — local environment, container build process, and CI pipeline execution. 

**🛠 Tech Stack**

Python 3
Flask
Docker
Git
GitHub Actions
Linux (WSL)
