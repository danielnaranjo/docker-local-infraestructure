# Docker As Local Infrastructure

### How to use

```
docker ps
docker images
docker-compose up -d 
docker-compose down
```

### Common usage


MongoDB server
```
MONGO_URI=mongodb://localhost:27017/test
```

PostgreSQL server
```
Server host: localhost
Port: 5432
User name: postgres
Password: secure_pass_here
```

Redis
```
REDIS_REST_URL=127.0.0.1:6379
```


### Docker common usages

```
docker ps 
docker ps -a
docker container prune
docker rmi <container id>
docker rmi <container id> -f
docker inspect
docker logs
```