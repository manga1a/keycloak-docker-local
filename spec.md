# Run Keycloak on Docker compose
Run Keycloak in docker as composed environment
## Requirements
1. Run PostgreSQL docker image.
    1. Use official docker image from docker hub: https://hub.docker.com/_/postgres
    2. Specify a username, and password
    3. Set a volume name so everytime the docker compose is run, it uses the same database files
2. Run Keycloak docker image
    1. Get official Bitnami docker image from: https://hub.docker.com/r/bitnami/keycloak
    2. Specify the DB parameters from requirement 1.
