# Spring-Framework
Sample Spring Framework with all basic concepts

#Installation and setup of the project

1. Install STS(Spring Tool Suite)
-> https://spring.io/tools

2. Create a maven project
-> select maven-archetype-quickstart

4. Open pom.xml file
-> Add ependencies
{
    <!-- https://mvnrepository.com/artifact/org.springframework/spring-context -->
    <dependency>
        <groupId>org.springframework</groupId>
        <artifactId>spring-context</artifactId>
        <version>5.2.6.RELEASE</version>
    </dependency>
}

It will add all JAR files related to Spring in the Maven Dependencies Folder
