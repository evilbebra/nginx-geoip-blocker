# nginx-geoip-blocker

### Description:
In a Docker Compose setup, there's a Java-based application and an Nginx server with embedded Lua. When a request is received, the application determines the country of origin for the request.

### Run:
```
1) git clone https://github.com/evilbebra/nginx-geoip-blocker
2) cd ./nginx-geoip-blocker
3) docker-compose up -d  
```
**-- FOR TEST. SHARES YOUR LOCAL APP TO GLOBAL INTERNET --**
```
4) ngrok.exe http 9999
```
5) follow the link that ngrok generated (like <https://your-public-ip.ngrok-free.app/>)
6) with RU and GB VPN you will get 500 error, from other countries it will give you the nginx start page