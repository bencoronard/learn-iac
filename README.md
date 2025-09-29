## Start a service
podman-compose -f <service.docker-compose.yml> up -d
## Pause a service
podman-compose -f <service.docker-compose.yml> stop
## Resume a service
podman-compose -f <service.docker-compose.yml> restart
## Stop a service
podman-compose -f <service.docker-compose.yml> down [--volume]