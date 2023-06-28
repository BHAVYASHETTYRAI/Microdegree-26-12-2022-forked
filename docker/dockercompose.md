docker-compose install
Copy the appropriate docker-compose binary from GitHub:

sudo curl -L https://github.com/docker/compose/releases/download/1.22.0/docker-compose-$(uname -s)-$(uname -m) -o /usr/local/bin/docker-compose
Fix permissions after download:
sudo chmod +x /usr/local/bin/docker-compose
Verify success:
docker-compose version
NOTE: to get the latest version (thanks @spodnet)
sudo curl -L https://github.com/docker/compose/releases/latest/download/docker-compose-$(uname -s)-$(uname -m) -o /usr/local/bin/docker-compose
