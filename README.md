# Streaming-data-with-Apache-Kafka-on-postgres-using-debezium-connector
## This is a project that shows the use of Apache Kafka in real time streaming database changes using python scripts from Postgres relational database with Debezium Postgres connector.
## Docker compose kafka file that connects Kafka, zookeeper, schema registory, kafka Manager and Debezium was used for this project. Thunder client was used to interact with the vairous API to validate their vairous requests.
## Debezium Postgres connectors captures role level database changes and stream data to Kafka via Kafka connect
## postgres wal_level was changed from replica to logical to enable publish and subscribe model (Pub/sub)
## Postgres User was created and granted to CREATE and SELECT privileges respectively to be able to add and copy publications and table data
