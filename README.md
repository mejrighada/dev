# Springboot Angular 12 MySQL Docker CRUD Application

![java-logo](https://img.icons8.com/color/60/000000/java-coffee-cup-logo--v1.png)
![springboot-logo](https://img.icons8.com/color/60/000000/spring-logo.png)
![maven-logo](https://img.icons8.com/ios/60/000000/maven-ios.png)
![docker-logo](https://img.icons8.com/color/60/000000/docker.png)
![mysql-logo](https://img.icons8.com/fluency/60/000000/mysql-logo.png)
![restapi-logo](https://img.icons8.com/nolan/60/api-settings.png)
![kubernetes-logo](https://img.icons8.com/color/60/000000/kubernetes.png)

## Springboot Backend
The backend module is developed in **Java 8** with **Springboot support**.

The project was initialized through the [Spring Initializer](https://start.spring.io/) and uses some modules like JPA module through MySQL for db queries, Data Module with Hibernate and above all it uses Docker to compile and run the *.jar* file on a special container.

To build and run locally backend module locally, without using Docker, you can run two simple commands from the terminal (Windows user) or from bash shell (Unix/Linux user):
```bash
$ mvn clean install -U -DskipTest=true (to build project)
$ mvn spring-boot:run (to run project)
```

If, on the other hand, you prefer run everything with the support of a Docker's container, just run a simple command:
```bash
$ docker-compose up -d
```
## Angular Frontend
