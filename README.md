Using nginx as a reverse proxy for a flask app leveraging docker

1. Pull nginx container image from dockerhub
    docker pull nginx:1.13.7

2. Run the container with the exposed port 
    docker run --name nginx-proxy -d -p 80:80 nginx:1.13.7

3. Stop the running container
    docker stop nginx-proxy

4. Pull the python container
    docker pull python:3

5. Write the docker-compose + docker file

6. Stop running docker container
    docker stop <container name>

7. start the cluster with docker-compose
    docker-compose up -d 
