# flask-microservice-starter

A simple Flask backend microservice starter kit

## Building a docker image on Apple Silicon

1. `docker buildx create --use`
2. `docker buildx build --platform linux/amd64,linux/arm64 --push -t <tag_to_push> .`

## Running 

1. `pip install -r requirements.txt`
2. `flask run`
