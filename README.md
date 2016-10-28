# kafka-rest

[Kafka Rest Proxy](https://github.com/confluentinc/kafka-rest) in a Docker container

## Usage
To run, simply
```
docker run -p 8082:8082 --name kafka-rest --env ZK_CONNECTION_STRING=my.zookeeper.host.com:2181 frontporch/kafka-rest:latest
```
