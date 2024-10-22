## jdbc-connectivity-student 


# Technical Details
In this project, we are going to use below set of versions for demonstrations.
```shell
Spring Boot - 3.3.4
Spring - 6.1.12
Lombok - 1.18.34
```
### Building

The example can be built with
```shell
mvn clean install
```

### Running the example in your local
```shell
mvn clean spring-boot:run
```

### mysql Database
```shell
CREATE TABLE student1.student (
  studentId INT NOT NULL,
  studentName VARCHAR(45) NULL,
  studentAddress VARCHAR(45) NULL,
  PRIMARY KEY (studentId));
```
