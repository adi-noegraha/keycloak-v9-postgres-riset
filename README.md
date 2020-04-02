# keycloak-v9-postgres-riset :P
## Test Run Keycloak
## Step 1 Run Postgres
```bash
cd database
cek environment di file docker-compose.yml
sudo docker-compose up
```

## Step 2 Run Keycloak
```bash
cd keycloak
cek environment di file docker-compose.yml
sudo docker-compose up
```
## Step 3 [Run TRaefik](traefik/Readme.md)

## Step 4 Test Keycloak
```bash
browse ke http://<domain>/auth
isi username dan password <admin/admin>
selanjutnya baca dokumentasi contoh kesini https://www.keycloak.org/getting-started/getting-started-docker
test aplikasi ke sini https://www.keycloak.org/app/

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

