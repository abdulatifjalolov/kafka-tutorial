Apache-Kafka tutorial

1. download Apache-Kafka https://kafka.apache.org/quickstart
2. unzip file and open it on cmd
3. start-zookeeper-server:
       .\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties
4. open another cmd and cd file then start-kafka-server:
       .\bin\windows\kafka-server-start.bat .\config\server.properties
5. clone project from Git https://github.com/abdulatifjalolov/kafka-tutorial and run project
6. POST http://localhost:8080/api/v1/send?message=helloApacheKafka and check console
