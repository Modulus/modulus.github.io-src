Title: Exposing data
Date: 2017-03-15 23:32
Category: app
Tags: kafka, step, docker, app, angular
Slug: steps_web
Summary: Guide for launching a web app pulling data from Kafka

#*1. Launch the web app container*
![webUP](/images/steps/web/web-up.png)

#*2. Open the browser*
![Start kafka and zookeper](/images/steps/web/stream.png)
Point your browser to *http://machine_ip/stream*

You should see the results of the second notebook filling the browser window. Take a look into the *kafka-web-app/app* folder. The application is built in *Python*, using *Flask*, and there is an html template and accompanying *js* that is subscribing to the Kafka topic, and messages are sent asynchronously to the frontend.

The application can be modified to receive handle this data in a different way. What else can you build with it?


##Finished!
That concludes this step by step guide

[Home](/) |
