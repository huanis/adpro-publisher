## AMQP
There are 5 data the publisher program will send to the message broker when it is ran once. This is because there are 5 messages published in main.rs. Each are considered as one data sent to the queue.

The url is the same as in the subscriber, however, in the publisher, it is used on new_queue_publisher. In the subsciber, it is used on new_queue_listener. This means that the data sent by the publisher to the queue will be received by the subscriber.