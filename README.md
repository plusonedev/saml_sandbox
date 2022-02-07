Get started at: https://github.com/keycloak/keycloak-containers
and: https://github.com/keycloak/keycloak-containers/blob/16.1.1/server/README.md

tl;dr
docker build -t keycloak:latest .
docker run -e KEYCLOAK_USER=<USERNAME> -e KEYCLOAK_PASSWORD=<PASSWORD> keycloak:latest
