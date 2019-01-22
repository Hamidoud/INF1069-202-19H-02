

```
$ docker-compose exec kafka kafka-topics \
             --zookeeper zookeeper:32181 --topic first_topic --create \
             --partitions 3 --replication-factor 1
```
