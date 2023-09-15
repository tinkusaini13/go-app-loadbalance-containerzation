# Nginx Load balancing Sample

> Go application load balanceing using docker compose

## How To Run
1. Edit line 2 and 3 in file ./nginx/nginx.conf
2. Change  172.31.38.64  to your docker ip and then save
3. Open a terminal and go to project
```bash
$ cd {go-to-project}
```
4. Execute docker compose
```bash
$ docker-compose up -d
```
5. Open browser
```bash
$ http://public-ip:8080

         
