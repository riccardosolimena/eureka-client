# Getting Started
This repo is part of teaching presented on Udemy Platform by [Udemy.com/riccardo-solimena](https://www.udemy.com/user/riccardo-solimena/).
For info and question contact me on [riccardo.solimena@gmail.com](mailto:riccardo.solimena@gmail.com).


### What this project does
This is an application that works as a simple eureka-client using Spring Cloud Eureka

### How to use it
Download the project and run the application. The application is configured in order to have a different random port for each runned instance. The runned application need that the project eureka-server or an Eureka Server in general is up and running in order to be connected.
In the application.properties file is possible to configure the eureka-server URL by default set as localhost:8761/eureka/. For multiple instances add the other servers comma separated. 

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Actuator](https://docs.spring.io/spring-boot/docs/{bootVersion}/reference/htmlsingle/#production-ready)

### Guides
The following guides illustrate how to use some features concretely:

* [Service Registration and Discovery](https://spring.io/guides/gs/service-registration-and-discovery/)

* [Spring Cloud Netflix](https://cloud.spring.io/spring-cloud-netflix/reference/html/)

* [Spring Cloud Eureka Client](https://cloud.spring.io/spring-cloud-netflix/multi/multi__service_discovery_eureka_clients.html)

* [Building a RESTful Web Service with Spring Boot Actuator](https://spring.io/guides/gs/actuator-service/)