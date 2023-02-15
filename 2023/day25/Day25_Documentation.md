## Day 25: Complete Jenkins CI/CD Project - Continued with Documentation

### Introduction
This document outlines the steps for setting up Jenkins to automate the deployment of a GitHub repository to a remote server. With these instructions, you'll be able to set up a Jenkins job that will automatically deploy changes to your repository whenever they are pushed to GitHub.
Also this project can be a good start to your Devops Journey if you're thinking making use services like EC2 Jenkins, docker, GitHub etc

          Services used :
          1. EC2(ubuntu)
          2. Jenkins
          3. Docker
          4. GitHub


          Prerequisite :
          Before you begin, make sure you have the following:
          1)A GitHub repository
          2)Jenkins installed on the remote server
          3)Git installed on the Jenkins server
          4)A Jenkins job set up to build the repository
          
### Cloning the repository
***
To clone the repository, follow these steps:

Open your terminal or command prompt.
Navigate to the directory where you want to clone the repository.

Run the following command:
  `git clone https://github.com/<username>/<repository>.git`
  
Replace `<username> `and `<repository>` with the appropriate values for your repository.

****Refer:** **Project url**** = <https://github.com/sayalijadhav091/node-todo-cicd.git>

**Table of Contents for Project:**  1)Fork this repository
                                    2)Generate SSH key
                                    3)Configuring GitHub
                                    4)Configuring GitHub-Webhook
                                    5)Installing GitHub integration plugin
                                    6)Configuring Jenkins

**Prerequisite:** 
Start the EC2 Instance and install 1)Docker 2)docker-compose 3)Java , jdk , jre. 4)jenkins & configure jenkins on localhost 5)GitHub Webhook integration

**Things to take a Note of** 1)Location of Project 2) Presence of Dockerfile & docker-compose file in the folder Directory

**Link to Refer a project:** <https://sayali.hashnode.dev/day24complete-jenkins-cicd-project>
