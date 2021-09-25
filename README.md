# How to run details service

## Prerequisite

## Build Docker Image for details service
```bash
docker build -t reviews .
```

## Run details service on port 8081
```bash
docker run -d --name reviews -p 8082:9080 -e ENABLE_EXTERNAL_BOOK_SERVICE=true details
```