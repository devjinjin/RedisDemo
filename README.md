# .net core/blazor Redis 샘플 코드

아래 redis 환경을 맞춘후 소스코드를 통해 테스트를 한다

##Docker (redis)
```
docker run --name my-redis -p 5002:6379 -d redis

docker ps -a

docker exec -it my-redis sh

redis-cli
```

### redis-cli 테스트
```
ping
=>PONG

dbsize
=> (integer) 0

scan 0
=> 1) "0"
2) (empty array)
```


