# Install Let's Encrypt SSL Certificate using Docker, MySQL, nginx and Wordpress on Contabo VPS

### Dependencies
- Wordpress 5.7
- PHP 7.3
- nginx
- Let's Encrypt SSL Certificate

### Setup
1. Modify environment in ```docker-compose.yaml```
1. Set ```.env``` variables to desired configuration
   
   > Note: Remove nginx config files if running test certificate before changing to production.
2. `docker compose -up`

---

Copy files to server (replace IP address with server address):

```scp -r ./* root@192.168.1.1:/root/project```
