FROM jenkins/jenkins

USER root

RUN apt update && apt upgrade && \
    apt install -y apt-transport-https ca-certificates curl software-properties-common && \
    curl -fsSL https://get.docker.com | bash - && \
    curl -L "https://github.com/docker/compose/releases/latest/download/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose && \
    chmod +x /usr/local/bin/docker-compose
