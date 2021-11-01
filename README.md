# Spring_boot_tu1

This code has be taken advantage of the course https://amigoscode.com/p/spring-boot and codes are mainl based on this project. 

Spring Boot Java project (IntelliJ Idea Ultimate, Java 17, Spring Boot, JPA)

This project contains Student Controller, Service, Repository and other elements
It consists of Client; GET, POST, PUT, DELETE Json commands in API LAyer, Service Layer, Data Access Layer, PostgresSQL Database

JSON commands; (StudentController.java -> action for URL -> generate request in HTTP client)

POST http://localhost:8080/api/v1/student
Content-Type: application/json

{
  "name": "John",
  "email": "john@gmail.com",
  "dob": "1997-10-11"
}

###

PUT http://localhost:8080/api/v1/student/1?name=Maria&email=maria@gmail.com
Content-Type: application/json

###

DELETE http://localhost:8080/api/v1/student/1

###

The results will be shown in here;
http://localhost:8080/api/v1/student


![alt text](https://github.com/cuneyterem8/Spring_boot_tu1/blob/master/image1.png?raw=true)

![alt text](https://github.com/cuneyterem8/Spring_boot_tu1/blob/master/image2.png?raw=true)

![alt text](https://github.com/cuneyterem8/Spring_boot_tu1/blob/master/image3.png?raw=true)


