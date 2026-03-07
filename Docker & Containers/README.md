# **DOCKER & CONTAINERS — SPOKEN VERSION**  

 1. **What is Docker?**

    > Docker is a containerization platform used to package applications.
    > It bundles application code with all dependencies.
    > So the application runs the same in every environment.
    > Docker containers are lightweight and start very fast.
    > It is widely used in DevOps for application deployment.

##
2. **What is Containerization?**

    > Containerization is a method of packaging applications with required libraries and dependencies.
    > It allows applications to run in isolated environments called containers.
    > These containers share the host operating system.
    > They are lightweight and consume fewer resources.
    > It helps to maintain consistency across development and production.

##
3. **What is a Docker Image?**

    > A Docker Image is a blueprint used to create containers.
    > It contains application code, runtime, libraries, and dependencies.
    > Images are built using Dockerfile instructions.
    > Once created, images are stored in Docker registries.
    > Containers are launched using these images.

##
4. **What is a Docker Container?**

    > A Docker Container is a running instance of a Docker image.
    > It runs the application in an isolated environment.
    > Containers share the host operating system kernel.
    > They are fast, portable, and use minimal system resources.
    > Multiple containers can run on the same host.

##
5. **What is a Dockerfile?**
   
    > Dockerfile is a text file used to build Docker images.
    > It contains step-by-step instructions to create the image.
    > We define the base image and install required packages.
    > Then we copy application files and set environment variables.
    > Finally, we specify the command to start the application.

##
6. **How do you reduce Docker image size?**

    > I use lightweight base images like Alpine Linux.
    > I remove unnecessary packages after installation.
    > I combine multiple commands into single layers.
    > I use multi-stage builds to keep only required files.
    > Smaller images improve performance and deployment speed.

##
7. **What is the difference between Docker and Virtual Machine?**

    > Docker containers share the host operating system.
    > Virtual Machines run their own full operating system.
    > Containers are lightweight and start in seconds.
    > Virtual Machines are heavier and take more time to start.
    > Containers are better for microservices and DevOps workflows.

##
8. **What is Docker Hub?**

    > Docker Hub is a public registry for Docker images.
    > It allows users to store and share container images.
    > Developers can download ready-made images from it.
    > It supports version control of images.
    > It helps teams collaborate easily.

##
9. **What is a Private Docker Registry?**

    > Private Docker Registry is used to store private images securely.
    > It is used inside organizations.
    > Only authorized users can access these images.
    > It improves security and control.
    > Examples include Azure Container Registry and Amazon ECR.
