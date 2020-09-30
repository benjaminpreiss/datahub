# datahub

## List of technologies used

- Ansible - Automate the deployment process and provide a code based server configuration
- k3OS - Underlying operating system to run all the docker containers (Nextcloud, bitwarden, traefik etc.)
- Openstack - Cloud computing platform used as infrastructure to host on
- Nextcloud - Cloud storage solution running via docker
- Bitwarden - Password manager running via docker
- Traefik - Loadbalancer in front of  nextcloud and bitwarden running on docker

## Information on repository file structure

The following is a brief explanation of the files and folders in this repository:

1. `friction_log.md` - A file where I log the friction encountered in the complete process of making things work.

## Prerequisites

1. Existing openstack account
2. Physical device with k3OS installed.
