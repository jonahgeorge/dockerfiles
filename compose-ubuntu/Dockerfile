FROM ubuntu:16.04
RUN apt-get update && apt-get install curl -y
RUN curl -L "https://github.com/docker/compose/releases/download/1.25.0/docker-compose-$(uname -s)-$(uname -m)" -o /bin/docker-compose
RUN chmod +x /bin/docker-compose
ENTRYPOINT ["/bin/docker-compose"]
