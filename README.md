# Microservices
A microservice is a software development technique that structures an application as a collection of small, independent, and loosely coupled services. Microservices are easier to understand, modify, and test than monolithic applications, making them more maintainable over time

Synchronous communication is one of the communication patterns used in microservices architecture where a client sends a request to a service and waits for a response. The communication is typically done through a well-defined API, such as REST or gRPC.

Asynchronous Communication
In this type of communication, the client does not wait for a response, instead, it just sends the message to the message broker. AMQP (like RabbitMQ) or Kafka can be used for asynchronous communication across microservices to achieve eventual consistency.
