# docker-neo4j

## 起動方法

```shell
docker-compose -f docker-compose.yml build
docker-compose -f docker-compose.yml up
```

その後、下記のような感じで起動されるので、http://localhost:7474/でブラウザ起動可能
```shell script
Starting docker-neo4j_core1_1 ... done
Attaching to docker-neo4j_core1_1
core1_1  | Active database: graph.db
core1_1  | Directories in use:
core1_1  |   home:         /var/lib/neo4j
core1_1  |   config:       /var/lib/neo4j/conf
core1_1  |   logs:         /logs
core1_1  |   plugins:      /plugins
core1_1  |   import:       /var/lib/neo4j/import
core1_1  |   data:         /var/lib/neo4j/data
core1_1  |   certificates: /var/lib/neo4j/certificates
core1_1  |   run:          /var/lib/neo4j/run
core1_1  | Starting Neo4j.
core1_1  | 2019-10-07 08:21:41.274+0000 WARN  Unknown config option: dbms.mode
core1_1  | 2019-10-07 08:21:41.311+0000 INFO  ======== Neo4j 3.5.11 ========
core1_1  | 2019-10-07 08:21:41.326+0000 INFO  Starting...
core1_1  | 2019-10-07 08:21:45.738+0000 INFO  Bolt enabled on 0.0.0.0:7687.
core1_1  | 2019-10-07 08:21:48.285+0000 INFO  Started.
core1_1  | 2019-10-07 08:21:49.784+0000 INFO  Remote interface available at http://localhost:7474/
```