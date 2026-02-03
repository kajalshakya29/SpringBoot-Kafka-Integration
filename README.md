# Kafka Message Producer (Spring Boot)
This is a simple Spring Boot application that acts as a Kafka Producer. It allows you to send messages to a Kafka topic via a REST API.

### Features- 
- Spring Boot integration with Apache Kafka.
- REST Endpoint to publish messages dynamically.
- Asynchronous message processing using CompletableFuture.
- Custom port configuration (9494).

### Tech Stack
- Java 17
- Spring Boot
- Apache Kafka
- Maven

### Prerequisites
- Before running the application, make sure you have:
- Kafka & Zookeeper installed and running on localhost:9092.
- The topic "kajal-topic1" created (or auto-creation enabled).

### API Endpoint
- To publish a message, send a GET request to: http://localhost:9494/producer-app/publish/{your_message}
- Example: http://localhost:9494/producer-app/publish/HelloWorld
  
### About Author
- Kajal Shakya- Java Backend Developer
- Github- https://github.com/kajalshakya29
- Linkedlin- https://www.linkedin.com/in/kajal-shakya-417485243/
