


 
 

 
JBoss Fuse Tutorial - Apache Camel + Spring + ActiveMQ + JBoss Fuse


What is JMS
Java Message Service (JMS) is an application program interface (API) that supports the formal communication known as messaging between computers in a network. The messages involved exchange crucial data between computers - rather than between users - and contain information such as event notification and service requests asynchronously.

What is ActiveMQ  

 
ActiveMQ is a message oriented middleware. It is an open source message broker written in Java together with a full Java Message Service (JMS) client. It provides "Enterprise Features" which in this case means fostering the communication from more than one client or server.

What is JMS Queue
Queue follows point-to-point, or p2p messaging model which allows users to send messages both asynchronously and synchronously using different channels. In this model once a message is received by the consumer, the message is destroyed as per p2p messaging model.

What is JMS topic
Topic follows Publish-and-subscribe, or pub/sub messaging model which allows the producer to send messages to many users at the same time. Consumers can subscribe to a particular topic, or channel, and receive all messages within the chosen topic. This model is asynchronous.

Here we will be developing a sample web app using spring JMS having a producer and consumer which will produce and consume message from two different queue.

https://www.javainuse.com/camel/camel_activeMQ

https://www.slideshare.net/ceposta/devops-with-activemq-camel-fabric8-and-hawtio

#   t e s t C a m e l  
 