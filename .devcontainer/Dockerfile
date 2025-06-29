FROM mcr.microsoft.com/devcontainers/typescript-node:1-22-bookworm

ENV PNPM_HOME="/home/node/.local/share/pnpm"
ENV PATH="$PNPM_HOME:$PATH"

RUN apt-get update -y && \
    apt-get upgrade -y && \
    npm i -g npm@latest && \
    npm i -g pnpm@latest && \ 
    pnpm add -g @antfu/ni@latest npm-check@latest
