# node-docker

# Build docker image
`docker build -t my-node-docker:v1.0 .`

# Start docker
`docker run --rm --name test-docker -p 8080:4000 my-node-docker:v1.0`

# How to debug inside a docker container
`docker exec -it test-docker bash`

# How to use docker compose
## > Start
`docker compose up` or `docker compose up -d` if we wanna run in detached mode
## > Stop
`docker compose down`
