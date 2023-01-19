# Eureka-Server

- Eureka Server is an application that holds the information about all client-service applications.
- Every Micro service will register into the Eureka server and Eureka server knows all the client applications running on each port and IP address.
- Eureka Server is also known as Discovery Server.

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
