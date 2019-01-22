

```bash
$ docker-compose exec kafka kafka-topics \
             --zookeeper zookeeper:32181 --topic first_topic --create \
             --partitions 3 --replication-factor 1
```
Reponse 

```
WARNING: Due to limitations in metric names, topics with a period ('.') or underscore ('_') could collide. To avoid issues it is best to use either, but not both.
Created topic "first_topic".
```

