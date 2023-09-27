# keycloak-compose

Run keycloak and postgresql with docker compose

This repo is set for my blogs

[Run Keycloak in docker with extenal DB](https://medium.com/@ozbillwang/run-keycloak-in-docker-with-extenal-db-1b504ad00eae)

[Run Keycloak locally with Docker compose](https://medium.com/@ozbillwang/run-keycloak-locally-with-docker-compose-db9a9f2fb437)

## Commands

```
    docker run -d --name mykeycloak -p 8080:8080 -e KEYCLOAK_ADMIN=admin -e KEYCLOAK_ADMIN_PASSWORD=password keycloak --verbose start  --hostname-strict=false --optimized  --http-enabled=true --db-url="jdbc:postgresql://<postgresql_db_hostname>/keycloak" --db-username=keycloak --db-password=password

```
