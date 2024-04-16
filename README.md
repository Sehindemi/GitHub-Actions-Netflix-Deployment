# GitHub-Actions-Netflix-Deployment
- Deployed a Netflix clone application via the use of the GItHub Action CICD
- Deployed a Netflix clone application via the use of the GItHub Action CICD
- SonarQube will be integrated with GitHub Actions and will be be used for code analysis and will be used to scan any issues with the code 
- EC2 is used to host our SelfHosted GitHub action runner for that 
- Trivy File scanner will be used to scan the docker file before running it on our local self hosted github runner
- GitHub Actions will be used to build the docker images and we'll be able to push the docker images 
- Trivy Image scan will be used to scan the Docker image 
![image](https://github.com/Sehindemi/GitHub-Actions-Netflix-Deployment/assets/97199481/10476d92-6896-4eca-8700-c46b808f33d9)

On the EC2 Instance we'll Install Sonarqube which would integrate with GitHub action to run the test, then after this I installed GitHub self hosted runner on the ec2 instance which was used to pull the images which we created using docker build then trivy Image scan was used to scan the Docker image which will then be used to run a docker container which will then allow us to see the Netflix-clone

Source code 
https://github.com/Sehindemi/Netflix-clone-Project

Overall Outcome
![image](https://github.com/Sehindemi/GitHub-Actions-Netflix-Deployment/assets/97199481/126cca61-3c96-4c74-a3e0-05213b061834)
