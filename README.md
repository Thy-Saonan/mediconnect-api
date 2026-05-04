# MediConnect API

Backend REST API for **MediConnect** — Spring Boot 4 on Java 25.

## Prerequisites

- JDK 25
- MySQL 8+

## Quick Start

```bash
# configure DB in src/main/resources/application.properties
./mvnw spring-boot:run
```

App runs at `http://localhost:8080`. Swagger UI at `/swagger-ui.html`.

## Common Commands

```bash
./mvnw test       # run tests
./mvnw verify     # tests + Checkstyle + SpotBugs
./mvnw clean install
```

## Recommended VSCode Extensions

⭐ required · 👍 recommended

| Extension | Purpose | |
| --- | --- | --- |
| `redhat.java` | Core Java Language Server | ⭐ |
| `vscjava.vscode-java-pack` | Java extension pack | ⭐ |
| `vscjava.vscode-java-debug` | Java debugger | ⭐ |
| `vscjava.vscode-java-test` | Run JUnit tests | ⭐ |
| `vscjava.vscode-java-dependency` | View project dependencies | ⭐ |
| `vscjava.vscode-maven` | Maven goals and lifecycles | ⭐ |
| `shengchen.vscode-checkstyle` | Real-time Checkstyle | ⭐ |
| `sonarsource.sonarlint-vscode` | Real-time bug detection | ⭐ |
| `eamodio.gitlens` | Git history and blame | 👍 |
| `redhat.vscode-xml` | XML support for `pom.xml` | 👍 |
| `humao.rest-client` | Test REST endpoints via `.http` files | 👍 |
| `usernamehw.errorlens` | Inline error display | 👍 |
| `vmware.vscode-spring-boot` | Spring Boot dashboard & bean navigation | |
| `vscjava.vscode-lombok` | Lombok annotations support | |
| `vscjava.vscode-gradle` | Gradle support (not needed — Maven only) | |
