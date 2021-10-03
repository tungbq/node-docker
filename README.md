# node-docker

# Build docker image
`docker build -t my-node-docker:v1.0 .`

# Start docker
`docker run --rm --name test-docker -p 8080:4000 my-node-docker:v1.0`
