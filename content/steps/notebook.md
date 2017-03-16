Title: Data Analysis
Date: 2017-03-15 23:45
Category: jupyter
Tags: jupyter, python, docker
Slug: steps_notebook
Summary: Guide for running jupyter container

#*1. Start the Jupyter Notebook container*
![Start kafka and zookeper](/images/steps/kafka/kafka1.png)
After running the container you will get a link with an authentication token of the form *https://localhost:8888/<token>*. Replace localhost for the ip of the machine you got on the credentials we printed out for you, and use your browser to open up the remote Jupyter interface.

#*2. Checkout the first notebook - Kafka-spark.ipynb*
![Kafkacat1](/images/steps/kafka/kafka2.png)
Open the first notebook -*Kafka-spark.ipynb*- from the Jupyter interface. The instructions are self-contained in the notebook. You will have permissions to modify its contents so be careful in deleting cells. You will also have permissions to create new notebooks for later.


#*3. Checkout the second notebook - Kafka-spark-publisher.ipynb*
Ther second notebook is adapted from the first, and has additional code for publishing back results to a Kafka topic from a stream. Open the second notebook - *Kafka-spark-publisher.ipynb* - and follow the contained instructions. Remember you can check if the topic is being filled using kafkacat (*tip: the topic is called Twitter.processed*)


#*4. Bonus tasks*
- Can you get tweets from #booster2017?
- Can you find top authors?
- What else can we use from the tweet?
- Is there enough data to plot a map for example? (coordinates or location)

[Home](/) | [Step by step guide]({filename}/steps/index.md) | [Next using the web app]({filename}/steps/web.md)
