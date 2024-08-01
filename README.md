# Docker

Container image examples

## Working with Containers

Verify the container is running:
```
docker container ls
docker ps
```

Exec into the container:
```
docker exec -it 4a84510f12f6 bash
docker exec -it -u root 4a84510f12f6 bash
```

View container logs:
```
docker logs instance_name
docker logs 4a84510f12f6
```

Shutdown the container:
```
docker stop 4a84510f12f6
```

