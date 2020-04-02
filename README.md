# keycloak-v9-postgres-riset :P
## Test Run Keycloak
## Run Postgres
```bash
cd database
cek environment di file docker-compose.yml
sudo docker-compose up
```

## Run Keycloak
```bash
cd keycloak
cek environment di file docker-compose.yml
sudo docker-compose up
```

## Project Structure
```
├── keycloak/
|   └── docker-compose.yml    
|   └── ..   
├── database/
|   └── docker-compose.yml   
|   └── ..   
├── traefik/
|   └── docker-compose.yml 
|   └── cert/
|        └── fullchain.pem
|        └── privkey.pem
```

