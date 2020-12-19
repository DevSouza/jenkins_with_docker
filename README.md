### Create Docker image

If you haven't built Jenkins' image, run:
```
docker build -f Dockerfile -t devsouza01/docker_with_jenkins:latest .
```

### Start Image with docker compose

If you want to start a container with a docker compose:
```
docker-compose -f docker-jenkins.yml up
```

