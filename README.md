# Jenkins-CICD-Pipelines

In this project, we will integrated Jenkins with many Devops Toolstools like Maven (as a build tool), NodeJS, Github as code repository, Sonarqube as code quality check, Dependency check to run vulnerability scan on librairies, Docker for building and pushing Docker images, and Kubernetes ad deployment server.

1- Create our Jenkins Server in AWS

![Screenshot 2024-04-15 224234](https://github.com/adrydry/Jenkins-CICD-Pipelines/assets/102819001/88835a99-5fa3-4ab3-bb05-438f0c860857)

2- Connect our machine with Mobaxterm and Set up our Jenkins server on port 4035

![1](https://github.com/adrydry/Jenkins-CICD-Pipelines/assets/102819001/378a80d3-85a0-4128-b8a1-a87565ecadcb)

3- Access our Jenkins Server from the browser

![1](https://github.com/adrydry/Jenkins-CICD-Pipelines/assets/102819001/ab06a1aa-54c1-41ff-af6f-90af768298cb)

4- Insert the password and install the suggested plugins. 
Our Jenkins server set up is now complete

![1](https://github.com/adrydry/Jenkins-CICD-Pipelines/assets/102819001/876e3c26-1b93-4012-974b-c9657dd635e9)

5- Go to Manage Jenkins
Go to Plugins (Available plugins), and Depending on which tool l want to integrate with Jenkins, choose the plugins and install them
For JDK: Choose Eclipse Temurin installer and open Jdk Native Plugins
For Owasp: Owasp dependency check
For Docker: Docker, Docker Pipeline, Docker build step, Cloudbees Docker build and Publish
For Sonarqube: Sonarqube check

![1](https://github.com/adrydry/Jenkins-CICD-Pipelines/assets/102819001/5ae80602-ffb5-4d21-8d5e-628bf3cc9ce5)

6- Configure all the tools in our Jenkins server
After downloading all the plugins of our pipelines, we need to configure each tool in our jenkins server.
For that, go to Global tool configuration
