# Spring in Action 5 Book Projects

* Spring, Spring Boot, JPA, JDBC, MySQL, Oracle, H2, DB

Those are the project codes for Spring in Action, Fifth Edition, by Craig Walls [Spring in Action 5](https://www.manning.com/books/spring-in-action-fifth-edition)
#

1.  [Chapter-1. Getting started with Spring](https://github.com/Hamdambek/Spring-in-Action-5-Book-All-Projects/tree/master/Chapter1_Getting%20started%20with%20Spring)
    
    * Maven project provides Spring Boot and Spring Web Initialize thymeleaf
     
     
2. [Chapter-2. Developing web app](https://github.com/Hamdambek/Spring-in-Action-5-Book-All-Projects/tree/master/Chapter2_Developing%20web%20app)
     * The project provides Spring Boot and JDBC template (using MySQL) implementation. In case of, Spring Boot using Maven configuration, and DB (database) using JDBC (only template not JPA ). 

3.  [Chapter-3. Working with Data_JDBC](https://github.com/Hamdambek/Spring-in-Action-5-Book-All-Projects/tree/master/Chapter3_Working%20with%20Data_JDBC)
     * Taco pizza (which I called project name) project provides Spring Boot and JDBC template (using MySQL) implementation. In case of, Spring Boot using Gradle configuration, and DB (database) using JDBC (only template not JPA ). 
 
  -> [Chapter-3. Working with Data JPA](https://github.com/Hamdambek/Spring-in-Action-5-Book-All-Projects/tree/master/Chapter3_Working%20with%20Data%20JPA)
     * Taco pizza (which I called project name) project provides Spring Boot and JDBC template (using MySQL) implementation. In case of, Spring Boot using Maven configuration, and DB (database) using JDBC and JPA.  
 
 Important: 
 <dependency>
            <groupId>com.h2database</groupId>
            <groupId>org.hibernate</groupId>
            <artifactId>credit_card_number</artifactId>
            <artifactId>assertj-core</artifactId>
            <artifactId>lombok</artifactId>
            <artifactId>htmlunit-driver</artifactId>
  </dependency>
     <properties>
        <project.build.sourceEncoding>
            UTF-8</project.build.sourceEncoding>
        <project.reporting.outputEncoding>
            UTF-8</project.reporting.outputEncoding>
        <java.version>1.8</java.version>
    </properties>
 #
There is one folder for each chapter in the book—​except for chapters 11 and 12, which share a source folder—​each containing most or all of the sample code for that chapter.

This source code is available for download from the book’s page at Manning.com as well as in GitHub at [Projects](https://github.com/Hamdambek/Spring-in-Action-5-Book-All-Projects)

# IMPORTANT: Lombok
To avoid having to write and maintain what is mostly boilerplate Java code, I’ve elected to use Lombok in all of these examples. When building from the command line, using Maven, you shouldn’t encounter any problems, as Lombok is included as part of the build process. 
But you will very likely encounter issues if you import these projects into your IDE.

If, after importing the projects into your IDE, you see errors complaining about missing getters, setters, constructors, or log instance variables, it’s because Lombok is not installed in your IDE. 
These bits of code will be generated by Lombok automatically, but your IDE doesn’t know that and complains that they are missing.
Indeed, you may observer Maven (pom.xml) file and all dependecy. In that project we should use Intellij Idea. 

To fix the errors, simply install Lombok. Lombok has support for most common (and arguably a few uncommon) IDEs, so no matter which IDE you use, you should be covered. See [Lombok](https://projectlombok.org/setup/overview )  for details on installing Lombok in your IDE.

# InAddition 
In that folder, you can donwload [Spring](https://github.com/Hamdambek/Spring-in-Action-5-Book-All-Projects/tree/master/InAddition), and Annotation explanations. 

 
# Thymeleaf

