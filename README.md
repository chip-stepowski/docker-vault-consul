This repo uses docker compose to setup a Vault server with a Consul backend, for quick and easy testing. 

<em>Note: Consul is running in <code>dev</code> mode, so once the container is stopped, data will be lost.</em>

To use:
1. Clone the repo to your local machine.
2. Ensure Docker is running.
3. Run `docker-compose up`

# Helpful commands
* Check the status of Vault:
<code>vault status</code>
* Get all Vault KV in Consul: 
<code>consul kv get -recurse -keys vault/ </code>