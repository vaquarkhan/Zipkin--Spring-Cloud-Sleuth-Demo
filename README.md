# Spring Cloud Sleuth Zipkin Demo

## Run application

```
cd tracedemo
./gradlew bootRun
```

## Run Zipkin server

```
cd zipkin 
./gradlew bootRun
```

Visit [http://localhost:9411/](http://localhost:9411/) to see zipkin dashboard


## Trace

```
curl http://localhost:8080/callhome
```

## Aliyun Container Service Deployment

Deploy use docker-compose.yml



----------------------------------------------------------------

https://spring.io/blog/2016/02/15/distributed-tracing-with-spring-cloud-sleuth-and-spring-cloud-zipkin

https://www.linkedin.com/pulse/zipkin-distributed-tracing-troubleshoot-latency-vaquar-khan-?trk=mp-reader-card
