# SNS vs SQS

![img](https://camo.githubusercontent.com/f4a574f56962b61983678d0cf73bd6d43911f17fbfb7f39e1dab1623108454e9/687474703a2f2f646f63732e6177732e616d617a6f6e2e636f6d2f736e732f6c61746573742f64672f696d616765732f736e732d66616e6f75742e706e67) 


- SNS is a distributed publish-subscribe system. Messages are pushed to subscribers as and when they are sent by publishers to SNS.

- SQS is distributed queuing system. ... Polling inherently introduces some latency in message delivery in SQS unlike SNS where messages are immediately pushed to subscribers.


* Messages can't be received by multiple receivers at the same time. Any one receiver can receive a message, process and delete it. Other receivers do not receive the same message later. Polling inherently introduces some latency in message delivery in SQS unlike SNS where messages are immediately pushed to subscribers. SNS supports several end points such as email, SMS, HTTP end point and SQS. If you want unknown number and type of subscribers to receive messages, you need SNS.

- Entity Type

    SQS: Queue (Similar to JMS)

    SNS: Topic (Pub/Sub system)


- Message consumption

   SQS: Pull Mechanism - Consumers poll and pull messages from SQS
   
   SNS: Push Mechanism - SNS Pushes messages to consumers