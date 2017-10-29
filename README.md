# RESTful-web-service-Java
A simple RESTful web service using Spring framework which returns a greeting request in json format.

## Build
To build the JAR file
```
$ ./gradlew build
```

## Run
Run the application using Gradle
```
$ ./gradlew bootRun
```

Run using the JAR file
```
$ java -jar build/libs/gs-rest-service-0.1.0.jar
```


## Sample Run

#### Default Greeting
Localhost web address that accepts HTTP GET requests
```
http://localhost:8080/greeting
```

JSON Response
```
{"id":10,"message":"Hello, World!"}
```

#### Greeting with name
Localhost web address that accepts HTTP GET requests
```
http://localhost:8080/greeting?name=Marios
```

JSON Response
```
{"id":11,"message":"Hello, Marios!"}
```
