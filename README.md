# Dog Cat Classification
![Dog Cat Classification](https://socialify.git.ci/Prikshit7766/Dog-Cat-Classification/image?language=1&name=1&pattern=Solid&stargazers=1&theme=Auto)

# Deployment - Demo

https://user-images.githubusercontent.com/101416953/233361759-cb60357e-37e7-4c50-b0c9-caf2aa073d05.mp4

# Run Locally

Clone the project

```bash
  git clone https://github.com/Ryzxxl/bbc-news-classification-mlops.git
```

Go to the project directory

```bash
  cd Dog-Cat-Classification
```

Install dependencies

```bash
  pip install -r requirements.txt
```

To run the **Flask App**
```bash
  python app.py
```

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

# Dockerizing Application

```bash
  docker build -t appname:latest .
  docker run -p 8080:8080 appname:latest
```
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

# Deployment

## To deploy this project on EC2 with Docker

```bash
#optinal
    sudo apt-get update -y 
    sudo apt-get upgrade 

#Required
    curl -fsSL https://get.docker.com -o get-docker.sh
    sudo sh get-docker.sh
    sudo usermod -aG docker ubuntu
    newgrp docker

```
## Configure your EC2 as self-hosted runner

## Setup github secrets
```bash
AWS_ACCESS_KEY_ID= {{ AWS_ACCESS_KEY_ID}}

AWS_SECRET_ACCESS_KEY= {{AWS_SECRET_ACCESS_KEY}}

AWS_REGION = {{AWS_REGION}}

AWS_ECR_LOGIN_URI = demo>> 566373416292.dkr.ecr.ap-south-1.amazonaws.com

ECR_REPOSITORY_NAME = demo>> simple-app
```
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
