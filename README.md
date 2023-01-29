# Kafka-Demo-Application
Simple kafka application that uses confluent cloud server

Refernce: https://developer.confluent.io/get-started/java/

First run producer through command:
java -cp build/libs/kafkafirst-0.0.1.jar examples.ProducerExample kafkafirst/src/main/resources/getting-started.properties

Then run consumer through command:
java -cp build/libs/kafkafirst-0.0.1.jar examples.ConsumerExample kafkafirst/src/main/resources/getting-started.properties
