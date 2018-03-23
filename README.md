# Online Bookshop


The repo contains the server and client sides of the Online Bookshop project.

## --!! This project is not complete yet, but you can review the code structure. !!--

### The pages for the components will be added with the next update.

With this project, you will be able to:

- User Signup and Login

- User profile management

- Product Management

- Shopping Cart

- Order checkout and order history

- Automatic email confirmation


## Our Stack
* [MySQL](https://www.mysql.com/)
* [Java 8](https://www.oracle.com/java/)
* [Spring Boot 1.5.2](https://spring.io/)
* [Hibernate](http://http://hibernate.org/)
* [Redis 3.0.4](https://redis.io/) - Please wait for the next update for more effective use.
* [AWS RDS](https://aws.amazon.com/rds/) - Please wait for the next update for more effective use and other aws services.
* [Thymeleaf](https://www.thymeleaf.org/)
* [Angular 5](https://angular.io/)
* [Angular CLI](https://github.com/angular/angular-cli)


## Installation (for development)

### The pages for the components will be added with the next update.
~~ ### **Admin Portal side:** ~~

1. Run `npm install -g angular-cli` to install angular-cli.
2. Run `npm install` to install dependencies.
3. Run `ng serve --port=4242` to fire up dev server.
4. Open browser at [http://localhost:4242](http://localhost:4242).

~~ ### **Front Store side:** ~~

1. Run `npm install -g angular-cli` to install angular-cli.
2. Run `npm install` to install dependencies.
3. Run `ng serve` to fire up dev server.
4. Open browser at [http://localhost:4200](http://localhost:4200).

### **Server side:**

1. You can configure AWS RDS with right crendtials or you can easily create your local mysql instance and define bookstoreapi schema to start!

2. Configure mail sender in backend application

  The email username and password will be in `/src/main/resources/application.properties`.

3. Install the project
  ```
  mvn clean install
  ```

4. Run it
  ```
  java -jar target/bookshop-0.0.1-SNAPSHOT.jar
  ```
  We take the target from the `pom.xml` file, and run it like: `target/<artifactId>-<version>.jar`.

  Then go to [http://localhost:8181](http://localhost:8181) (the server port can be changed in `/src/main/resources/application.properties` at `server.port` argument).

## Tests

**Client side:**

  * Not yet..

**Server side:**

  * Not yet..


## License

ISC
