# Using docker
- `cd` (change directory) to be in the root folder
- Build a docker image `docker build -t devops-test .`
- Start a docker container on port 8081 `docker run -d -p 3001:80 --restart always devops-test`
- visit [localhost:3001](http://localhost:3001)

# Using docker-compse
- Run the docker-compose CLI command: `docker-compose up -d`
- visit [localhost:3001](http://localhost:3001)