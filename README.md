## 运行

  ```bash
  docker pull waltonmax/postgresql:latest
  
  docker run -d --name postgresql --network host -e POSTGRES_PASSWORD=postgres waltonmax/postgresql:latest
  
  #docker-compose
  docker-compose up -d
  
  ```

## 进入容器

```bash
docker exec -it postgresql bash
```
