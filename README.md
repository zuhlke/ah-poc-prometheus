# ah-poc-prometheus

Edit the `prometheus.yml`, then build the Docker image and optionally push it to Docker Hub.

## Build and Run
```
docker build -t my-prometheus .
docker run -p 9090:9090 my-prometheus
```
