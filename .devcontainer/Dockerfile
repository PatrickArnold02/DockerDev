FROM mcr.microsoft.com/devcontainers/javascript-node:22-bookworm

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends gnupg2 zsh

RUN su node -c "npm install -g npm-check-updates better-commits"