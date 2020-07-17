# Spring-Framework
Sample Spring Framework with all basic concepts

Credit: "This project is inspired by spring Framework for Beginners with Spring Boot by Naveen Reddy"


#Installation and setup of the project

1. Install STS(Spring Tool Suite)  
-> https://spring.io/tools

2. Create a maven project  
-> select maven-archetype-quickstart

4. Open pom.xml file
-> Add spring-context dependency from maven repo  
https://mvnrepository.com/artifact/org.springframework/spring-context/5.2.6.RELEASE

  It will add all JAR files related to Spring in the Maven Dependencies Folder

# Spring Boot

Create new Spring Starter Project
#Dependency Injection

instead of creating the object of the class we can inject the new instance using getBean method of ApplicationContext class  
Eg.   
ApplicationContext appContext =  SpringApplication.run(DemoApplication.class, args);  
Student st = appContext.getBean(Student.class); //Injecting new instance  
