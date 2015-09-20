# docker-compose-samples


#### Zookeeper and Kafka
```sh
$  docker-compose -f ./kafka-zookeeper_compose.yml -p zookeeperAndKafka up -d
$  docker-compose -f ./kafka-zookeeper_compose.yml -p zookeeperAndKafka stop
```

#### Zookeeper and Kafka with REST
```sh
$  docker-compose -f ./kafka-zookeeper-rest_compose.yml -p zookeeperAndKafkaWithRest up -d
$  docker-compose -f ./kafka-zookeeper-rest_compose.yml -p zookeeperAndKafkaWithRest stop
```
