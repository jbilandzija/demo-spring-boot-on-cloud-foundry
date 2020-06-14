## Service Discovery Server - Netflix Eureka

##### Further information can be found on:
* [spring.io/service-registration-and-discovery](https://spring.io/guides/gs/service-registration-and-discovery/)
* [baeldung.com/spring-cloud-netflix-eureka](https://www.baeldung.com/spring-cloud-netflix-eureka)

##### Getting started
* Locally the application will be exposed on ``localhost:8761``
* You may need to run with Spring profile ``ldev``
* Configuration repository can be found here: [github.com/jbilandzija/spring-boot-microservice-demo-configs](https://github.com/jbilandzija/spring-boot-microservice-demo-configs)

##### Run application
* `mvn springboot:run`
* via Docker
    * run  `./docker-build.sh` to build a docker image
    * run  `./docker-run.sh` to ruin the spring boot container
    * stop the container with `./docker-stop.sh`
    * make sure you give your shell scripts execution rights: `` chmod +x``
