Title: Workshop guide
Date: 2017-03-11 12:26
Category: Workshop
Tags: workshop, docker-compse, jupyter
Slug: workshop-index
Summary: Workshop guide, here we show you how to use docker-compse, jupyter

Here is a guide on how to start consuming tweets with kafka. We have created a setup for you using docker-compose

#*1. Open two terminal windows and ssh into your machine*

* [SSH Guide for mac]({filename}/mac/ssh_screenshots.md)
* [SSH Guide for Windows]({filename}/win/putty.md)

#*2. Change directory to you workshop folder*
![Workshop folder](/images/workshop/workshop_folder.png)

#*3. run "docker-compose up"*
![Docker compose up](/images/workshop/docker-compose_up.png)

#*4. Wait for the output to stop, it should look like this*
![Kafka wait](/images/workshop/kafka-wait.png)

#*5. Change to your second window and run the following*
![kafkacat](/images/workshop/kafkacat.png)

##*You should se output from kafka like this*
![kafka-twitter](/images/workshop/kafkacat-twitter.png)

#*6. Go to the docker-comopse window, and scroll up*
![Jupyter access](/images/workshop/jupyter.png)
*You are looking for the jupyter access url*

#*7. Open a browers window and enter the url*
![addres](/images/workshop/jupyter-address.png)
*Replace "localhost" with the ip address you have on you note*

#*8. You will get a warning like this*
![warning https](/images/workshop/jupyter-warning.png)

#*9. Click advanced and accept the self signed sertificate*
![Accept](/images/workshop/jupyter-accept.png)

#*10. You are now logged in to jupyter*
![Jupyter](/images/workshop/Jupyter_logged_in2.png)

#*11. Choose the notebook you want to run*
![Jupyter1](/images/workshop/kafka-notebook1.png)

#*12. Click "Cell" and then "Run all" to run the whole notebook*
![Jupyter1](/images/workshop/kafka-notebook2.png)

#*13. If you scroll down, you will shortly see the output*
![Jupyter1](/images/workshop/kafka-notebook3.png)
*This could take a few minutes, please be patient*

#*14. After a short while, you should se an output similar to this*
![Jupyter1](/images/workshop/kafka-notebook4.png)

#*You are now done*
This concludes the workshop guide

[Home]({filename}/index.md) |
[Home win]({filename}/win/index.md) |
[How to use putty]({filename}/win/putty.md) |
[How to use winscp]({filename}/win/winscp.md)
