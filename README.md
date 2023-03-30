# This will install containers in new network with static Ip addresses

# Clone this repository:
```
git clone https://github.com/t7o7n7y/containers-network.git
```
# Run command:
```
sudo docker compose up -d
```
# or
```
sudo docker-compose up -d
```
# For Nginx type in your browser:
```
localhost:8888
```
# For check IP addresses run in your terminal:
```
sudo docker inspect mysql-container | grep "IPv4Address"
```
```
sudo docker inspect nginx-container | grep "IPv4Address"
```

