# Reflection
### a. What is amqp?
`amqp` stands for Advanced Message Queuing Protocol, which is an open standard application layer protocol for message-oriented middleware. The defining features of AMQP are message orientation, queuing, routing (including point-to-point and publish-and-subscribe), reliability, and security.

### b. What does it mean? guest:guest@localhost:5672 , what is the first guest, and what is the second guest, and what is localhost:5672 for?
`guest:guest` represents the username and password for authenticating with the AMQP server.
The first `guest` is the username, the colon separates the username from the password, and the second `guest` is the password.
This is the default credential pair for RabbitMQ.

While `localhost:5672` specifies where the AMQP server is running:
`localhost` means the server is running on the same machine as the code, and
`5672` is the port number the AMQP server is listening on (this is the default port for AMQP)