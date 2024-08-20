FROM mcr.microsoft.com/devcontainers/universal:2-linux

# Install the xz-utils package
RUN apt-get update && \
    apt-get install -y xz-utils && \
    pip install django

# Install MongoDB
RUN apt-get install -y mongodb

# MongoDB port
EXPOSE 27017