# Install Let's Encrypt SSL Certificate using Docker, MySQL, nginx and Wordpress on Contabo VPS

Install Docker WordPress container with nginx, MySQL, and Let's Encrypt SSL Certificate.

### Requirements
- Docker
- Docker Compose

### Setup
1. Modify environment in ```docker-compose.yaml```
1. Set ```.env``` variables to desired configuration
   
   > Note: Remove nginx config files if running test certificate before changing to production.
2. `docker-compose up`

---

Copy files to server (replace IP address with server address):

```scp -r ./* root@192.168.1.1:/root/project```
