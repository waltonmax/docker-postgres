## 运行

  ```bash
  dock build -t waltonmax/postgresql:latest .
  
  docker pull waltonmax/postgresql:latest
  
  docker run -d \
      --name=postgresql \
      --net=host \
      -e POSTGRES_PASSWORD=postgres \
      -v /data/postgresql/data:/var/lib/postgresql \
      waltonmax/postgresql:latest
  
  #docker-compose
  docker-compose up -d
  
  ```

## 进入容器

```bash
docker exec -it postgresql bash
```
