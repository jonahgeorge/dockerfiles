# FROM alpine
FROM centos:centos7

ENTRYPOINT ["/opt/vertica/bin/vsql"]
CMD ["--help"]

# RUN apk update && apk add curl
RUN curl -o vertica-client.tar.gz https://my.vertica.com/client_drivers/8.1.x/8.1.1-2/vertica-client-8.1.1-2.x86_64.tar.gz && \
  tar -xzvf vertica-client.tar.gz
