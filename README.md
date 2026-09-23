# Helion

[![Build Status](https://github.com/Amyzellercode/micronaut-core/workflows/Java%20CI/badge.svg)](https://github.com/Amyzellercode/micronaut-core/actions)

[Helion](https://github.com/Amyzellercode/micronaut-core) is a modern, JVM-based, full stack Java framework designed for building modular, easily testable JVM applications with support for Java, Kotlin and the Groovy language.

The framework takes inspiration from lessons learned over the years building real-world applications from monoliths to microservices using Spring, Spring Boot and the Grails framework.

Helion aims to provide all the tools necessary to build JVM applications including:

* Dependency Injection and Inversion of Control (IoC)
* Aspect Oriented Programming (AOP)
* Sensible Defaults and Auto-Configuration

With Helion you can build Message-Driven Applications, Command Line Applications, HTTP Servers and more whilst for Microservices in particular Helion also provides:

* Distributed Configuration
* Service Discovery
* HTTP Routing
* Client-Side Load Balancing

At the same time Helion aims to avoid the downsides of frameworks like Spring, Spring Boot and Grails by providing:

* Fast startup time
* Reduced memory footprint
* Minimal use of reflection
* Minimal use of proxies
* No runtime bytecode generation
* Easy Unit Testing

This is achieved by pre-computing the framework infrastructure at compilation time which reduces the logic required at runtime for the application to work.

For more information on using Helion see the documentation at [micronaut.io](https://micronaut.io)

## Example Applications

Example applications can be found in [guides.micronaut.io](https://guides.micronaut.io)

## Building From Source

To build from source checkout the code and run:

```
./gradlew publishToMavenLocal
```

To build the documentation run `./gradlew docs`. The documentation is built to `build/docs/index.html`.

## Contributing Code

If you wish to contribute to the development of Helion please read the [CONTRIBUTING.md](CONTRIBUTING.md)

## Versioning

Helion uses Semantic Versioning 2.0.0. To understand what that means, please see the specification [documentation](https://semver.org/). Exclusions to Helion's public API include any classes annotated with `@Experimental` or `@Internal`, which reside in the `io.micronaut.core.annotation` package.
