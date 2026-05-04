# Automated CI/CD DevOps Project

A fully automated pipeline that deploys a Flask application to AWS EC2 using Docker and GitHub Actions.

## Tech Stack
* **Cloud:** AWS (EC2)
* **Containerization:** Docker
* **CI/CD:** GitHub Actions
* **Registry:** Docker Hub
* **Web Framework:** Python Flask

## How it Works
1. Code is pushed to GitHub.
2. **GitHub Actions** triggers a build.
3. A **Docker image** is created and pushed to **Docker Hub**.
4. The **AWS EC2** instance pulls the latest image and runs the container.