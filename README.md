# dc-Authentik
This repository contains the configuration for deploying Authentik using Docker Compose on an Ubuntu server.

Prerequisites
Ubuntu server
Docker and Docker Compose installed
Git installed
nginx proxy

Deployment Steps
1. set up and define services in docker-compose.yml
2. Install pwgen for password generation
3. set up environment variables
4. Start Services
   - docker compose pull
   - docker compose up -d
5. Verify Deployment
   - http://your server's IP or hostname:9000/if/flow/initial-setup/
