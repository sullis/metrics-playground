# metrics-playground

A Java playground for experimenting with metrics libraries and observability tooling.

## Technologies

- **Java 21**
- **[Micrometer](https://micrometer.io/)** – application metrics facade
- **[JUnit Jupiter](https://junit.org/junit5/)** – unit and integration testing
- **[Testcontainers](https://testcontainers.com/)** – container-based integration tests
- **[AWS SDK for Java v2](https://aws.amazon.com/sdk-for-java/)** – AWS service clients
- **[Apache Commons](https://commons.apache.org/)** – utility libraries
- **[SLF4J](https://www.slf4j.org/) / [Logback](https://logback.qos.ch/)** – logging

## Requirements

- Java 21+
- Maven 3.x

## Build

```bash
mvn clean package
```

## Test

```bash
mvn clean test
```

## License

Apache License 2.0 – see [LICENSE](LICENSE) for details.
