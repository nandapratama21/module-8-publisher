1. How many data your publisher program will send to the message broker in one
   run?
Answer: Based on main.rs code, the main function initializes a publisher p and sends 5 messages to the message broker in one run.

2. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber
   program, what does it mean?
Answer: The url "amqp://guest:guest@localhost:5672" is used to connect to the RabbitMQ server. The url is the same in the subscriber and publisher programs, which means that both the publisher and subscriber programs are connecting to the same RabbitMQ server.

This is my screen that running RabbitMQ
![screenshot1.png](screenshot1.png)