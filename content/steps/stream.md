Title: Streaming data from twitter
Date: 2017-03-15 23:32
Category: twitter
Tags: twitter, step, docker
Slug: steps_twitter
Summary: Guide for using streaming data from twitter

#*1. Go to twitter and create an application*
Go to: [https://apps.twitter.com/](https://apps.twitter.com/)

#*2. Click "Create new app"*
![twitter1](/images/steps/stream/twitter1.png)

#*3. Fill in the details*
![twitter details](/images/steps/stream/twitter-app1.png)

#*4. Generate access keys*
![keys gen](/images/steps/stream/twitter-app2.png)
*Click "Generate my access token", the topmost tokens (Consumer key and secret) should be generated up front*

#*5. Results should look like this*
![keys](/images/steps/stream/twitter2.png)
*Should look like this*

#*6. Edit your docker-compose.yml inside the workshop folder*
![compose](/images/steps/stream/twitter3.png)
*Add your keys like this*
*PS! these keys are fake and wont work...*

#*7. Start the container*
![Start the container](/images/steps/stream/kafka.png)

#*8. You should see a similiar output like below"*
![Start kafka and zookeper](/images/steps/stream/kafka_2.png)
*These are live tweets from twitter streaming in*

[Home](/) |  [Step by step guide]({filename}/steps/index.md) | [Next using jupyter]({filename}/steps/notebook.md)
