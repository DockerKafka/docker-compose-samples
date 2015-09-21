# docker-compose-samples


#### Express startup:
```sh
$  wget -q -O - https://raw.githubusercontent.com/DockerKafka/docker-compose-samples/master/kafka-zookeeper-rest-manager_compose.yml | docker-compose -f - -p expressUp up -d
```

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

#### Zookeeper and Kafka with manager
```sh
$  docker-compose -f ./kafka-zookeeper-manager_compose.yml -p zookeeperAndKafkaWithManager up -d
$  docker-compose -f ./kafka-zookeeper-manager_compose.yml -p zookeeperAndKafkaWithManager stop
```

#### Zookeeper and Kafka with rest REST and manager
```sh
$  docker-compose -f ./kafka-zookeeper-rest_compose.yml -p zookeeperAndKafkaWithRestAndManager up -d
$  docker-compose -f ./kafka-zookeeper-rest_compose.yml -p zookeeperAndKafkaWithRestAndManager stop
```
