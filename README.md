
# ah-poc-prometheus

Edit the `prometheus.yml`, then build the Docker image and optionally push it to Docker Hub.

[![Build Status](https://travis-ci.com/zuhlke/ah-poc-prometheus.svg?branch=master)](https://travis-ci.com/zuhlke/ah-poc-prometheus) 

## Build and Run
```
docker build -t aimlesshammer/ah-poc-prometheus .
docker run -p 9090:9090 aimlesshammer/ah-poc-prometheus
```


## Push To Docker Hub
```
docker push aimlesshammer/ah-poc-prometheus:latest
```

## Deploy to PCF
```
cf push ah-poc-prometheus --docker-image=aimlesshammer/ah-poc-prometheus:latest
```