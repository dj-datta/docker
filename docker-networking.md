### Docker Network Types:
1. Bridge
2. Host
3. Null
4. Macvlan
5. Overlay

**create docker network**
````
docker network create <net-name>
````
**list networks**
````
docker network ls
````
**attach network to container**
````
docker run -itd --network vnet  --name cont1 nginx
````
