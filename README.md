[![CircleCI](https://circleci.com/gh/ankurprasad711/dockercourse4udacity.svg?style=svg)](https://circleci.com/gh/ankurprasad711/dockercourse4udacity)

# Operationalize a Machine Learning Microservice API.

## Project Overview

This project deploys a containerized Python flask application. The purpose of this application is to serve predictions on housing prices through sklearn Model API. Sklearn model has been trained to predict housing prices in Boston area .Sklearn Model uses various parameters to predict the prices.

### Project Tasks

project goal is to operationalize this working, machine learning microservice using [kubernetes](https://kubernetes.io/), which is an open-source system for automating the management of containerized applications.

* Test your project code using linting
* Complete a Dockerfile to containerize this application
* Deploy your containerized application using Docker and make a prediction
* Improve the log statements in the source code for this application
* Configure Kubernetes and create a Kubernetes cluster
* Deploy a container using Kubernetes and make a prediction
* Upload a complete Github repo with CircleCI to indicate that your code has been tested


### Getting Started
---

## Setup the Environment

* Create a virtualenv and activate it
```   
python3 -m venv <your_venv>
source <your_venv>/bin/activate
```
* Run `make install` to install the necessary dependencies

### Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`

### Kubernetes Steps

* Setup and Configure Docker locally
* Setup and Configure Kubernetes locally
* Create Flask app in Container
* Run via kubectl
