<div align='center'>
  <img height="60" src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/79/Spring_Boot.svg/640px-Spring_Boot.svg.png">
  <h1>🍃 Spring Boot Interview Questions</h1>

  <i>From zero to hero 🥷🏻</i>

  <sup>Leave a star ⭐️ if you like the project</sup>

  <strong>[Buy me a coffee](https://www.buymeacoffee.com/29LK03m9CB) ☕️<br />
</div>

---

## Index

- [Index](#index)
  - [Beginner](#beginner)
    - [What is Spring Boot?](#what-is-spring-boot)
    - [Key Features of Spring Boot](#key-features-of-spring-boot)
    - [What is Spring Boot Actuator?](#what-is-spring-boot-actuator)
    - [What is Spring Boot Starter?](#what-is-spring-boot-starter)
    - [What is Spring Boot CLI?](#what-is-spring-boot-cli)
    - [What is Spring Boot Initializr?](#what-is-spring-boot-initializr)
    - [What is Dependency Injection?](#what-is-dependency-injection)
    - [What is Spring Security?](#what-is-spring-security)
    - [What is Spring Data JPA?](#what-is-spring-data-jpa)
    - [What is Spring Cloud?](#what-is-spring-cloud)
    - [What is Spring Batch?](#what-is-spring-batch)
    - [Why is Spring “opinionated”?](#why-is-spring-opinionated)
    - [What does @EnableAutoConfiguration do? What about @SpringBootApplication?](#what-does-enableautoconfiguration-do-what-about-springbootapplication)

---

### Beginner

#### What is Spring Boot?

Spring Boot is a framework that allows you to create production-ready applications quickly. It simplifies the process of creating standalone, production-ready Spring-based applications. It extends the Spring framework, making it easier to create web applications and microservices quickly and with minimal configuration.

Spring Boot is particularly useful for developers looking to build microservices or web applications efficiently

Relevant Links:
- [Spring Boot Documentation](https://docs.spring.io/spring-boot/docs/current/reference/html/index.html)
- [Wikipedia](https://en.wikipedia.org/wiki/Spring_Boot)
- [Baeldung: What is Spring Boot?](https://www.baeldung.com/spring-boot)
- [Codecademy: What is Spring Boot?](https://www.codecademy.com/articles/what-is-spring-boot)

**[⬆️ Return to index](#index)**

---

#### Key Features of Spring Boot

- **Autoconfiguration:** Automatically configures your Spring application based on the dependencies you have added.
- **Standalone Applications:** Allows you to create applications that can run independently without needing an external server.
- **Opinionated Defaults:** Provides default configurations to help you get started quickly, while still allowing customization.
- **Embedded Servers:** Comes with embedded servers like Tomcat or Jetty, so you don’t need to deploy WAR files.

**[⬆️ Return to index](#index)**

---

#### What is Spring Boot Actuator?

Spring Boot Actuator is a sub-project of Spring Boot that provides production-ready features to help you monitor and manage your application. It provides a set of built-in endpoints, such as `/health`, `/info`, and `/metrics`, that you can use to monitor your application's health, configuration, and performance.

Some of the features provided by Spring Boot Actuator include:

- Application health checks
- Environment information
- Metrics
- Auditing
- Logging

Relevant Links:
- [Spring Boot Documentation: Actuator](https://docs.spring.io/spring-boot/docs/current/reference/html/actuator.html)
- [Baeldung: Spring Boot Actuator](https://www.baeldung.com/spring-boot-actuators)

**[⬆️ Return to index](#index)**

---

#### What is Spring Boot Starter?

Spring Boot Starters are a set of convenient dependency descriptors that you can include in your application's build configuration to get a set of dependencies quickly. Starters are a way to group dependencies together to provide a specific set of functionality. For example, you can use the `spring-boot-starter-web` starter to include all the dependencies you need to build a web application.

Starters simplify the process of adding dependencies to your project, as you only need to include a single starter instead of adding multiple dependencies manually.

Relevant Links:
- [Spring Boot Documentation: Starters](https://docs.spring.io/spring-boot/docs/current/reference/html/using-spring-boot.html#using-boot-starter)
- [Baeldung: Spring Boot Starters](https://www.baeldung.com/spring-boot-starters)

**[⬆️ Return to index](#index)**

---

#### What is Spring Boot CLI?

Spring Boot CLI (Command Line Interface) is a command-line tool that allows you to run Spring Boot applications directly from the command line. It provides a quick and easy way to prototype and develop Spring Boot applications without needing to set up a full project structure.

With Spring Boot CLI, you can create, run, test, and debug Spring Boot applications using a simple command-line interface. It also includes features like auto-restart, which automatically restarts your application when you make changes to the code.

Relevant Links:
- [Spring Boot Documentation: CLI](https://docs.spring.io/spring-boot/docs/current/reference/html/spring-boot-cli.html)
- [Baeldung: Spring Boot CLI](https://www.baeldung.com/spring-boot-cli)

**[⬆️ Return to index](#index)**

---

#### What is Spring Boot Initializr?

Spring Boot Initializr is a web-based tool that allows you to quickly generate a new Spring Boot project with the dependencies and settings you need. You can use Initializr to customize your project by selecting the project type, language, build tool, and dependencies you want to include.

Initializr generates a project structure for you based on your selections, including the necessary configuration files, build scripts, and dependencies. You can then download the project as a ZIP file and import it into your favorite IDE to start developing your Spring Boot application.

Relevant Links:
- [Spring Initializr](https://start.spring.io/)

**[⬆️ Return to index](#index)**

---

#### What is Dependency Injection?

Dependency Injection (DI) is a design pattern used to implement IoC (Inversion of Control), allowing the creation of dependent objects outside of a class and providing those objects to a class in various ways. It helps in making the code more modular, testable, and maintainable.

In Spring, DI can be achieved through constructor injection, setter injection, or field injection.

Relevant Links:
- [Spring Documentation: Dependency Injection](https://docs.spring.io/spring-framework/docs/current/reference/html/core.html#beans-dependency-injection)
- [Baeldung: Dependency Injection](https://www.baeldung.com/inversion-control-and-dependency-injection-in-spring)

**[⬆️ Return to index](#index)**

---

#### What is Spring Security?

Spring Security is a powerful and customizable authentication and access-control framework for Java applications. It provides comprehensive security services for Java EE-based enterprise software applications.

Spring Security is highly configurable and can be used to secure web applications, REST APIs, and method-level security.

Relevant Links:
- [Spring Security Documentation](https://docs.spring.io/spring-security/site/docs/current/reference/html5/)
- [Baeldung: Spring Security](https://www.baeldung.com/spring-security)

**[⬆️ Return to index](#index)**

---

#### What is Spring Data JPA?

Spring Data JPA is a part of the larger Spring Data family, which makes it easier to implement JPA-based repositories. It provides a framework that works with JPA to help you create repositories that are easy to test and maintain.

Spring Data JPA reduces the boilerplate code required to implement data access layers for various persistence stores.

Relevant Links:
- [Spring Data JPA Documentation](https://docs.spring.io/spring-data/jpa/docs/current/reference/html/)
- [Baeldung: Spring Data JPA](https://www.baeldung.com/the-persistence-layer-with-spring-data-jpa)

**[⬆️ Return to index](#index)**

---

#### What is Spring Cloud?

Spring Cloud provides tools for developers to quickly build some of the common patterns in distributed systems (e.g., configuration management, service discovery, circuit breakers, intelligent routing, micro-proxy, control bus, one-time tokens, global locks, leadership election, distributed sessions, cluster state).

Spring Cloud is designed to work well in a cloud environment and provides a set of tools to manage the complexity associated with distributed systems.

Relevant Links:
- [Spring Cloud Documentation](https://spring.io/projects/spring-cloud)
- [Baeldung: Spring Cloud](https://www.baeldung.com/spring-cloud)

**[⬆️ Return to index](#index)**

---

#### What is Spring Batch?

Spring Batch is a lightweight, comprehensive batch framework designed to enable the development of robust batch applications vital for the daily operations of enterprise systems. It provides reusable functions that are essential in processing large volumes of records, including logging/tracing, transaction management, job processing statistics, job restart, skip, and resource management.

Spring Batch is designed for processing large volumes of data in a consistent and reliable manner.

Relevant Links:
- [Spring Batch Documentation](https://docs.spring.io/spring-batch/docs/current/reference/html/)
- [Baeldung: Spring Batch](https://www.baeldung.com/spring-batch)

**[⬆️ Return to index](#index)**

---

#### Why is Spring “opinionated”?

Spring is considered "opinionated" because it provides a set of defaults and conventions that guide developers in building applications. These opinions are based on best practices and are designed to help developers get started quickly and build applications that follow industry standards.

Spring Boot, in particular, is opinionated in that it provides a set of defaults and auto-configurations that help developers build production-ready applications with minimal configuration. While Spring Boot is opinionated, it also allows developers to override these opinions and customize their applications as needed.

**[⬆️ Return to index](#index)**

---

#### What does @EnableAutoConfiguration do? What about @SpringBootApplication?

`@EnableAutoConfiguratio` annotation on a Spring Java configuration class
– Causes Spring Boot to automatically create beans it thinks you need
– Usually based on classpath contents, can easily override

```java
@Configuration
@EnableAutoConfiguration
public class MyAppConfig {
      public static void main(String[] args) {
      SpringApplication.run(MyAppConfig.class, args);
    `
}
```