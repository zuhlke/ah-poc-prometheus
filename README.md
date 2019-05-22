
# ah-poc-prometheus

Edit the `prometheus.yml`, then build the Docker image and optionally push it to Docker Hub.

[![Build Status](https://travis-ci.com/zuhlke/ah-poc-prometheus.svg?branch=master)](https://travis-ci.com/zuhlke/ah-poc-prometheus) 

## Pipeline

The travis pipeline will create a build image and push it to Docker Hub, then deploy the app to PCF.

## Deploy to PCF

`cf push`

## Build docker image locally

`./docker-build-image`
