This repo uses docker compose to setup a Vault server with a Consul backend.

# Troubleshooting
1. bind: address already in use
    - check to make sure there is not already another Vault service running
    - if none are running, use the following commands to clean up docker:
        - docker-compose down --remove-orphans
        - docker network prune -f