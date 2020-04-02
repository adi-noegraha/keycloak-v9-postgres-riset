## How To Run Traefik - SSL
Generate SSL di Certbot
```bash
sudo apt-get install software-properties-common
sudo add-apt-repository universe
sudo add-apt-repository ppa:certbot/certbot
sudo apt-get update
sudo apt-get install certbot
sudo ufw allow 80
certbot
sudo certbot certonly --standalone --preferred-challenges http
curl ifconfig.me
dig <nama_domain> @1.1.1.1
sudo ls /etc/letsencrypt/live/<nama_domain>
sudo certbot renew --dry-run
```
Buat folder cert
```bash
mkdir cert
cd cert
copy file fullchain.pem dan privkey.pem ke folder cert
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
