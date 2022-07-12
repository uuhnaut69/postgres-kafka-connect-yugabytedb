# postgres-kafka-connect-yugabytedb

Create source connector

```shell
curl  -i -X POST http://localhost:8083/connectors \
      -H 'Content-Type: application/json' \
      -H 'Accept: application/json' \
      -d @postgres-source-connector.json
```

Create sink connector

```shell
curl  -i -X POST http://localhost:8083/connectors \
      -H 'Content-Type: application/json' \
      -H 'Accept: application/json' \
      -d @yugabyte-sink-connector.json
```