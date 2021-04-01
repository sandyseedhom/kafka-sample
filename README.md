# kafka-sample

Sample Kafka producers and consumers written in Java

Producers: 
- ProducerDemo.java
- ProducerDemoKeys.java
- ProducerDemoWithCallback.java

Consumers:
- ConsumerDemo.java
- ConsumerDemoAssignSeek.java
- ConsumerDemoGroups.java
- ConsumerDemoWithThread.java

# How to run
1. In the kafka_2.13-2.7.0 directory, run zookeeper-server-start config/zookeeper.properties to begin zookeeper
2. In the same directory, run kafka-server-start config/server.properties to begin kafka
3. Run a consumer/producer class
