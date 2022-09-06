[![CircleCI](https://dl.circleci.com/status-badge/img/gh/jude-don/DevOps_Operationalizing-ML/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/jude-don/DevOps_Operationalizing-ML/tree/main)

## Project Overview

The DevOps Operationalizing ML project demonstrates the abilities gained through the Nanodegree to operationalize a Machine Learning Microservice, built on Scikit-Learn. The project's objective is to forecast housing costs in Boston using a variety of factors, including the typical number of rooms in a home, information on highway access, teacher-to-student ratios, and others. Visit Kaggle, on [the data source site](https://www.kaggle.com/c/boston-housing), to learn more about the data.

### What does the project entail?

* Create environment
* Create a docker container
* Run docker
* Upload container to docker hub
* Run the deployed application in a Kubernetes cluster
* Integrate with CirceCi


---

## Project Process

### Phase 1

* Download zip folder to your local machine



### Phase 2

* Create environment by editing your `Makefile` and running `make setup`. This will create an environment called `.devopss`
* Install all dependencis by running `make install`


### Phase 3

* Edit `run_docker.sh` file and run the application on docker by caling `bash run_docker.sh`


### Phase 4
* Edit `upload_docker.sh` by using your dockerhub usernme as the tag
* Run `bash upload_docker.sh` to upload it to docker hub


### Phase 5
* Edit the `run_kubernetes.sh` file and run the command `bash run_kubernetes.sh` to deploy to kubernetes
