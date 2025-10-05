# Spring Boot Hello API (Plain Java Project)

A simple Spring Boot REST API demonstrating multiple endpoints.

## Endpoints
- `GET /hello` → Returns "Hello from cs"
- `GET /bye` → Returns "Bye from the java World"
- `GET /greet?name=XYZ` → Returns personalized greeting
- `GET /info` → Returns profile info as JSON

## Technologies
- Java
- Spring Boot
- REST API

## How to Run
1. Make sure you have **Java 17+** installed.
2. Compile the project:
```bash
javac -cp "path/to/spring-boot-jars/*" src/com/example/demo/Hello.java
Run the application:

java -cp "path/to/spring-boot-jars/*:src" com.example.demo.Hello


Test endpoints in Postman or browser:

http://localhost:8081/hello

Author

Gangisetty Vishnu


**Tip:** If you want, I can **write a fully ready-to-paste LinkedIn post** that explains this plain Spring Boot project clearly for recruiters, including emojis, hashtags, and what you learned.  

Do you want me to do that?
