This repo uses docker compose to setup a Vault server with a Consul backend.

To use:
1. Clone the repo locally.
2. Ensure Docker is running.
3. Run `docker-compose up`

# Helpful commands
* Get all Vault KV in Consul: 
<code>consul kv get -recurse -keys vault/ </code>