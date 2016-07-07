Update nginx.conf and set your local IP in proxy_pass (line 24)

Start Kitematic

Execute : 
- docker-compose build
- docker-compose up

In Kitematic : 
- select the started container
- select Settings
- select Ports

Start SonarQube
Go to the IP on line 443 (for instance https://192.168.99.100:6443)