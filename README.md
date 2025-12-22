# Automated-CI-CD-pipelines-for-building-testing-and-deploying-applications-
Automated CI/CD pipelines for building, testing, and deploying applications using Jenkins, Docker, and GCP, improving deployment efficiency and reliability.

# Automated CI/CD Pipelines for DaveAi

## Description
Implemented **Automated CI/CD pipelines** for building, testing, and deploying applications at DaveAi. Pulled developer code from Bitbucket, built Docker images, and deployed containers on GCP using both manual and automated methods.

---

## Features
- Continuous Integration and Continuous Deployment (CI/CD) pipelines using Jenkins  
- Built Docker images from source code using Dockerfiles and Bash scripts  
- Configured pipelines to deploy containers on specific nodes  
- Pushed Docker images to **GCP Container Registry**  
- Deployed containers manually and via **Cloud Run**  
- Automated Docker orchestration using existing Bash scripts  
- Improved deployment efficiency, reliability, and scalability  

---

## Project Structure

1. `Jenkinsfile` – Defines CI/CD pipeline stages  
2. `docker/` – Dockerfiles for building images  
3. `scripts/` – Bash scripts for building and deploying containers  
4. `config/` – Jenkins and GCP configuration files  
5. `.gitignore` – Files and folders to ignore  

---

## Usage

1. Clone the repository:

    git clone https://github.com/Sainath-344/ci-cd-daveai.git
   
  cd ci-cd-daveai

3. Configure Jenkins with your Bitbucket repository credentials.

4. Set up Docker and GCP environment (Cloud Run, Container Registry).

5. Trigger Jenkins pipeline to automatically build, push, and deploy containers.

## Author
Sainath Reddy Ganadhipalli – DevOps / Cloud Engineer
