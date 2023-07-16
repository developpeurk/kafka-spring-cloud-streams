# kafka-spring-cloud-streams


### download kafka

[Kafka](https://kafka.apache.org/downloads)


````
C:\Tools\kafka_2.13-3.5.0>start bin\windows\zookeeper-server-start.bat config/zookeeper.properties

C:\Tools\kafka_2.13-3.5.0>start bin\windows\kafka-server-start.bat config/server.properties

C:\Tools\kafka_2.13-3.5.0>start bin\windows\kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic R1

C:\Tools\kafka_2.13-3.5.0>start bin\windows\kafka-console-producer.bat --broker-list localhost:9092 --topic R1

C:\Tools\kafka_2.13-3.5.0>start bin\windows\kafka-console-consumer.bat --bootstrap-server localhost:9092 --topic R4 --property print.key=true --property print.value=true --property key.deserializer=org.apache.kafka.common.serialization.StringDeserializer --property value.deserializer=org.apache.kafka.common.serialization.LongDeserializer

````