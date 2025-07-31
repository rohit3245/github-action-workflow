
# MERN Stack CI/CD Pipeline Project using GitHub Actions Workflows.

This repository demonstrates setting up an end-to-end CI/CD pipeline for a MERN (MongoDB, Express.js, React.js, Node.js) stack application using GitHub-Actions.

## Overview

This project showcases a comprehensive CI/CD pipeline that automates the build and deployment processes for a 3-tier MERN stack application.
I have created a GitHub-Actions Workflow which when triggered builds and pushes docker images to DockerHub with dynamnic version tags using the actions-build-id and deploys the application on an EC2 Instance which acts like a deployment server using a shell script and Docker-Compose.
Github-Actions was much more efficient in terms of speed of execution and compute resource utilization. Github-Actions uses YAML files for its pipeline script which is much more easier to begin with instead of Jenkins groovy scripts.
Checkout this same pipeline execution i have done using [Jenkins](https://github.com/YashPatil1609/MERN-CI-CD-Jenkins).

For detailed information, execution steps and comparison of Jenkins and Github-Actions please refer to my [blog post](https://yashpatilofficial.hashnode.dev/leveraging-efficient-workflows-of-github-actions-for-seamless-automation) and on [dev.to](https://dev.to/yash_patil16/leveraging-efficient-workflows-of-github-actions-for-seamless-automation-1ef9) where I provide step-by-step instructions and insights into each stage of the pipeline setup.
