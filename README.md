## Configuration Server

The server is built using [Spring Cloud](https://spring.io/projects/spring-cloud-config) 
which will act as a Server to externalize
and centralize the configurations used by different microservices.


Though the project says *Spring*, non-Java clients can consume the service too,
since behind the scenes it is just a server-client architecture, leveraging REST api-s.


