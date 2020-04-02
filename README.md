# keycloak-v9-postgres-riset :P

## How To Run Postgres
```bash
cd database
cek environment di file docker-compose.yml
sudo docker-compose up
```

## How To Run Keycloak
```bash
cd keycloak
cek environment di file docker-compose.yml
sudo docker-compose up
```

## Project Structure
```
├── keycloak/
|   └── docker-compose.yml    
|   └── tba   
├── database/
|   └── docker-compose.yml   
|   └── tba   
├── traefik/
|   └── docker-compose.yml 
|   └── cert/
         └── fullchain.pem
         └── privkey.pem
```

