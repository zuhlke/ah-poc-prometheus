
# ah-poc-prometheus

Edit the `prometheus.yml`, then build the Docker image and optionally push it to Docker Hub.

[![Build Status](https://travis-ci.com/zuhlke/ah-poc-prometheus.svg?branch=master)](https://travis-ci.com/zuhlke/ah-poc-prometheus) 

## Build and Run

### Automatically

Push to Git -- Travis will create build image and push to Docker Hub and then deploy to PCF

### Deploy to PCF

`cf push ah-poc-prometheus`
