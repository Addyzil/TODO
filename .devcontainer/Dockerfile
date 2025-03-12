FROM mcr.microsoft.com/devcontainers/javascript-node:20

# Install additional tools
RUN npm install -g npm@latest

# Set working directory
WORKDIR /workspace

# Install dependencies
COPY package.json package-lock.json ./
RUN npm install
