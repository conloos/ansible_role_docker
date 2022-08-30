# Ansible Role for configure container for hosting docker.

**summary**
This role is for configuring a container to run docker containers and install docker. 
Look in the tasks directory for each configuration.
All configurations are held atomically via their own files. 

## Variables that have to be defined

| variable | description |
| -------- | ----------- |
| docker_url | docker gpg url |
| docker_keyring | path to keyring |
| docker_repo | package repo infromation |

# lxd-container creation
You have to create the conainer with "security.nesting: True"


