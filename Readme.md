# Nodejs Apigee swagger2api - Dockerized

## Build:
```
docker build -t docker-apigee-swagger2api:latest .
```
## Run:
```
docker run -it --rm -e URL=${MY_AWESOME_URL} -e API_PROXY_NAME=${PROXY} docker-apigee-swagger2api:latest
```