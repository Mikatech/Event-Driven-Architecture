# Event-Driven-Architecture :fire:
The goal of this project is to learn the best practices w/ Event Sourcing &amp; Event Drive Architecture with building an application with CQRS & Event Sourcing design pattern.

# Resources :books:

- [Event Sourcing By Martin Fowler](https://martinfowler.com/eaaDev/EventSourcing.html)
- [Building Scalable App. with ES & CQRS by Okonkwo Vincent Ikem](https://andela.com/insights/building-scalable-applications-using-event-sourcing-and-cqrs/)

# Architecture :gear:

The project should implement:
- API gRPC + HTTP Gayeway
- Many Microservices (userManagementService, EmailNotificationService ...)
- A Kafka for event storing
- Each microservices can have a event handler which handle some events and update the postgresDB
- Each microservices can raise event and communicate with Kafka or Read date from the postgresDB
- Only the event handler can write in Postgres
- The microservices communicate with each other with gRPC, the HTTP gateway allows users to interact with the system

