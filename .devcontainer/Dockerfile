FROM mcr.microsoft.com/devcontainers/typescript-node:1-22-bookworm

# Install Neo4j CLI (optional)
RUN npm install -g neo4j-graphql-cli

# Install NestJS CLI
RUN npm install -g @nestjs/cli

# Install Angular CLI
RUN npm install -g @angular/cli

# Optional: Install other tools
RUN apt-get update && apt-get install -y git curl
