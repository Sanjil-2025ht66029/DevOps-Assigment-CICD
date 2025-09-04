# DevOps-Assigment-CICD
Introduction to DevOps Assignment.

Purpose of this repo is to demostrate the usage of Github Version Control, Github Actions CICD, Docker, DockerHuband Unit Test in Python.

This is a Flask app for Gym Fitness.

### Build application
Build the Docker image manually by cloning the Git repo.
```
$ git clone https://github.com/Sanjil-2025ht66029/DevOps-Assigment-CICD.git
$ docker build -t sanjilpradhan/devops-flask-app .
```

### View and Download Image from DockerHub
You can also download the existing image from [DockerHub](https://hub.docker.com/r/sanjilpradhan/devops-flask-app).
```
docker pull sanjilpradhan/devops-flask-app
```

### Run the container
Create a container from the image in port 5000
```
$ docker run --name my-container -d -p 5000:5000 sanjilpradhan/devops-flask-app
```

Now visit http://127.0.0.1:5000
```
 Hello, Welcome to the World of Gym and Fitness !!! 
```