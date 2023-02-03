# Docker Example
## docker
preview localhost [url](http://localhost:8080) 

```bash
docker build --tag docker-example --file dockerfile .
docker run -d -p "8080:80" -v $(pwd):/usr/share/nginx/html docker-example
```

## docker compose

```bash
docker-compose up --build -d
```
