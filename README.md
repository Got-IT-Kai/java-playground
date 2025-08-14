# Java Playground
This repository is a personal playground for experimenting with Java code.

It includes various examples, exercises, and projects to help improve Java programming skills.

## Key Learning Goals

The Primary focus of this repository is to enhance understanding of Java concepts, including:
* Build Tool
  * To effectively configure `Gradle` using the `Kotlin DSL`.
* Modern Java
  * Advanced Stream API
  * Lambda Expressions
  * Streams
  * Record Classes
  * Sealed Classes
  * Pattern Matching
  * Virtual Threads
* Spring Framework
  * Spring Boot
  * Spring Data JPA
  * Spring WebFlux
  * Project Reactor

## 💡 Project Philosophy

This project is organized into **self-contained packages**, each focusing on a specific concept or feature.

The goal is for each package to be an independent, runnable "mini-project."

This approach allows for focused experimentation without creating complex dependencies between different examples.

If necessary, utility code may be duplicated to ensure each package can be understood on its own.

```tree
.
├── modern-java
│   ├── records-and-sealed-types
│   ├── stream-api
│   ├── vritual-threads-performance
│   └── ...
├── spring-framework
│   ├── spring-data-jpa
│   ├── simple-rest-api
│   └── ...
└── reactive-programming
    ├── project-reactor-basics
    └── ...
```

## Getting Started
This project is configured with Java 21 and Gradle.

### Clone
git clone https://github.com/Got-IT-Kai/java-playground.git

### Build
./gradlew build
