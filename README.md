[![CircleCI](https://circleci.com/gh/michlin0825/Udacity_DevOps_Microservice.svg?style=svg)](https://circleci.com/gh/michlin0825/Udacity_DevOps_Microservice)

## Project Overview

The project objective is to operationalize a Machine Learning Microservice API. 

We are given a pre-trained, sklearn model that has been trained to predict housing prices in Boston according to several features. We operationalizes a Python flask app—in a provided file, `app.py`—that serves out predictions (inferences) about housing prices through API calls. 


## Files explanation
- config.yml: CircleCI configuration file for running the tests
- app.py: Python flask app that serves out predictions (inference) about housing prices through API calls
- Dockerfile: Dockerfile for building the image
- make_prediction.sh: Send a request to the Python flask app to get a prediction, for localhost
- Makefile: includes instructions on environment setup and lint tests
- run_docker.sh: file to be able to get Docker running, locally
- run_kubernetes.sh: file to run the app in kubernetes
- upload_docker.sh: file to upload the image to docker


## Setting up

* Run `make install` to install the necessary dependencies
* Run Docker:  `./run_docker.sh`
* Run Kubernetes:  `./run_kubernetes.sh`

