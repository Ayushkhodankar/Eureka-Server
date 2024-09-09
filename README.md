# Eureka-Server

- Eureka Server is an application that holds the information about all client-service applications.
- Every Micro service will register into the Eureka server and Eureka server knows all the client applications running on each port and IP address.
- Eureka Server is also known as Discovery Server.

<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhcMZBv7AZQvpLEMR7kO9p7QAR6gN7EsYQnkDJz6rG0m2sgCnflPr4rZoXwW8HZv2Y7KU9mMa_JHVen62eYiG81hNZYm1saPpfuBJGjlD-XMS0sMkpn9nHQYbFSaBoXwnPzxA0ac8j-L0irv85FEuu7KG2jFzzWMtl6FRnY0bv1XTVYTugS_SK9lDGD/s1920/Spring%20Boot%20Microservices.012.jpeg" alt="image"></img>

# In The Repository

This sample Eureka-server based repository consists of the following modules:
- **Eureka Server** - A Eureka Server is initialized and implemented in this module to handle the Client-APIs request.

This dependency in the pom.xml represents the Main Eureka Server Initialization.
### 
    <dependency>
    	<groupId>org.springframework.cloud</groupId>
			<artifactId>spring-cloud-starter-netflix-eureka-server</artifactId>
		</dependency>

- **diagnosis-service** - an API module that basically invokes services acknowlegded in diagnosis.

This dependency in the pom.xml represents the Eureka Client API Initialization.
### 
     <dependency>
			<groupId>org.springframework.cloud</groupId>
			<artifactId>spring-cloud-starter-netflix-eureka-client</artifactId>
		</dependency>
- **hospital-service** - an API module that basically shows and presents the services provided in hosspital arena.

This dependency in the pom.xml represents the Eureka Client API Initialization.
###
    <dependency>
			<groupId>org.springframework.cloud</groupId>
			<artifactId>spring-cloud-starter-netflix-eureka-client</artifactId>
		</dependency>


This Repository was built in :

1. Spring Tool Suite - 4
2. Eclipse 2022-12
3. Java Version - 1.8
4. JDK-17
5. Eureka-Server Dependency
