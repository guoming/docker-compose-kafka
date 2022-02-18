# Kafka
## 1、创建网络
``` SHELL
docker network create kafka
```

## 2、启动
``` SHELL
docker-compose up -d
```
## 3、访问测试
``` SHELL
telnet localhost 2101
telnet localhost 9092
```
 