Apache Kafka Tutorial
This tutorial will guide you through setting up Apache Kafka and running a sample project to demonstrate its functionality.

Step 1: Download Apache Kafka
Download Apache Kafka from the official website: Apache Kafka Downloads

Step 2: Unzip the Kafka Package
Unzip the downloaded Kafka package to a directory of your choice.

Step 3: Start Zookeeper Server
Open a command prompt and navigate to the Kafka directory. Start the Zookeeper server using the following command:
.\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties

Step 4: Start Kafka Server
Open another command prompt, navigate to the Kafka directory, and start the Kafka server using the following command:
.\bin\windows\kafka-server-start.bat .\config\server.properties

Step 5: Clone the Sample Project
Clone the sample Kafka project from the GitHub repository:
https://github.com/abdulatifjalolov/kafka-tutorial

Step 6: Run the Sample Project
Navigate to the cloned project directory and run the project.

Step 7: Send a Test Message
Send a test message to the Kafka server using a POST request to the following endpoint:

POST http://localhost:8080/api/v1/send?message=helloApacheKafka

Check the console of the Project to see the message received.
