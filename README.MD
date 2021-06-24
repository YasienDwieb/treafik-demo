# Traefik Demo

### Setup
- Start Traefik `docker compose up -d`
- Start apache server `docker compose -f docker-composer-services.yaml up -d`
- 
### Notes
- Add the following to your `/etc/hosts` file
    - `127.0.0.1    monitor.docker` to expose traefik dashboard
    - `127.0.0.1    apache.docker` to expose apache server