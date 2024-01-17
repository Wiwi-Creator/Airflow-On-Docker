根據Dockerfile 利用 docker-compose 建立Image
```
docker-compose up -d --build
```

# 確認執行中 Container
```
docker ps
```

# 登入 Web Server
- 在瀏覽器登入: http://localhost:8080/

# 登入 Flower Server
- 在瀏覽器登入: http://localhost:5555/

# Referance
[Docker Hub](https://hub.docker.com/)
[Apache Airflow(五)Scale out with Celery Executor](https://medium.com/sq-catch-and-note/apache-airflow-%E4%BA%94-scale-out-with-celery-executor-aed05a480b8)