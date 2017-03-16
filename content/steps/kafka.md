Title: Collecting Data
Date: 2017-03-15 23:32
Category: kafka
Tags: kafka, step, docker
Slug: steps_kafka
Summary: Start using kafka and test data collection

#*1. Open two terminal windows*

#*2. In window 1 - start the kafka and zookeeper containers*
![Start kafka and zookeper](/images/steps/kafka/kafka1.png)
This will start the containers. We have written a docker-compose file that makes it easier to get Kafka and Zookeper cooperating. The remaining components of the workshop are also included in the docker-compose file.

Take some time to investigate what is included in the docker-compose.yml file if you wish

#*3 In window 1 - use kafkacat to produce messages*
![Kafkacat1](/images/steps/kafka/kafka2.png)
Kafkacat will make it easier to consume and produce messages from and to Kafka. It is installed in the system already. Typing *kafkacat* by itself will give you a list of options.

#*4 Write some messages*
![Kafkacat1](/images/steps/kafka/kafka3.png)
Press [Enter] between each message you want to send.

*Note: ctlr+c ctrl+d will exit the program, but leave it on for now*

#*5 In window 2 - use kafkacat to read the messages*
![Kafkacat1](/images/steps/kafka/kafka4.png)

#*6 Kafkacat should produce an output like this*
![Kafkacat1](/images/steps/kafka/kafka5.png)
You can try keeping both windows open and producing messages between them.

*Hooray, you have just succesfully used Kafka for storing and retrieving messages. Ready for prime time? Click the next tutorial.* 



[Home](/) | [Step by step guide]({filename}/steps/index.md) | [Next streaming data]({filename}/steps/stream.md)
