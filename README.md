# Operationalize-a-Machine-Learning-Microservice-API 
This project is part of the Udacity Cloud Devops Nanodegree program.
In this project, a containerized flas application is deployed to serve out predictions about housing prices through API calls. Using an sklearn model that has been trained to predict housing in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios etc.

### Project Procedure
* Test project code using linting
* Complete a Dockerfile to containerize this application
* Deploy containerized application using Docker and make a prediction
* Configure Kubernetes and create a Kubernetes cluster
* Deploy a container using Kubernetes and make a prediction
* Upload a complete Github repo with CircleCI to indicate the code has been tested


### Breakdown of Files
- run_kubernetes.sh: file to run the app in kubernetes
- upload_docker.sh: file to upload the image to docker
- Dockerfile: Dockerfile for building the image
- config.yml: CircleCI configuration file for running the tests
- app.py: Python flask app that serves out predictions (inference) about housing prices through API calls
- make_prediction.sh: Send a request to the Python flask app to get a prediction, for localhost
- Makefile: includes instructions on environment setup and lint tests
- run_docker.sh: file to be able to get Docker running, locally


### Run the project