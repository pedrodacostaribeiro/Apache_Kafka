# Apache_Kafka
Apache Kafka is an open-source stream-processing software platfor for ral-time feeds.
 
## Apache Kafka on AWS EC2

- wget https://www.apache.org/dyn/closer.cgi?path=/kafka/2.1.0/kafka_2.11-2.1.0.tgz
- tar -xzf kafka_2.11-2.1.0.tgz
- cd kafka_2.11-2.1.0

start zookeper server 
bin/zookeeper-server-start.sh config/zookeeper.properties

start kafka server
bin/kafka-server-start.sh config/server.properties
