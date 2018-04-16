# AMQP-ssun28

Here are the main features of AMQP:

* Platform independent wire level messaging protocol
* Consumer driven messaging
* Interoperable across multiple languages and platforms
* It is the wire level protocol
* Have 5 exchange types direct, fanout, topic, headers, system
* Buffer oriented
* Can achieve high performance
* Supports long lived messaging
* Supports classic message queues, round-robin, store and forward
* Supports transactions (across message queues)
* Supports distributed transactions (XA, X/Open, MS DTC)
* Uses SASL and TLS for security
* Supports proxy security servers
* Meta-data allows to control the message flow
* LVQ not supported
* Client and server are equal
* Extensible


#### Usage


    1. RabbitMQ hello:
       $python send.py
       $python receive.py
       
       
    2. RabbitMQ Publish/Subscribe:(deliver a message to multiple consumers)
       $python receive_logs.py
       $python emit_log.py "info: This is the log message"
       

**References can be found at 
[https://dzone.com/articles/comparison-of-asynchronous-messaging-technologies](https://dzone.com/articles/comparison-of-asynchronous-messaging-technologies)
[https://github.com/rabbitmq/rabbitmq-tutorials/tree/master/python](https://github.com/rabbitmq/rabbitmq-tutorials/tree/master/python).**
