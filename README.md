# ansible-docker-install

Playbooks to install/remove Docker and deploy/destroy Swarm

Note: Swarm playbooks are not available yet

## Usage

Configure your inventory, with a `docker_nodes` host group, then run the playbook:

```
# Install Docker
$ ansible-playbook -i inventory.yml docker-install.yml

# Remove Docker
$ ansible-playbook -i inventory.yml docker-remove.yml
```

