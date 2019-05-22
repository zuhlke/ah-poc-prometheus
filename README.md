
# ah-poc-prometheus

[![Build Status](https://travis-ci.com/zuhlke/ah-poc-prometheus.svg?branch=master)](https://travis-ci.com/zuhlke/ah-poc-prometheus) 

## Build docker image locally

This uses the publically available `prom/prometheus` image, adding in the local `prometheus.yml` configuration file.

`./docker-build-image`

## Run prometheus locally

This makes a prometheus instance accessible at http://localhost:9090

`./docker-run-locally`

## Deploy to PCF

`cf push`

## Pipeline

The travis pipeline will create a build image and push it to Docker Hub, then deploy the app to PCF.


