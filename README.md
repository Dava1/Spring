# Spring

> hello, I'm building a small Spring Boot app for messaging, auth, and simple web interactions.

This project is a Java-based Spring Boot application that combines Spring MVC, Spring Security, Spring Data JPA, and PostgreSQL. It provides a lightweight user system with registration, login, message posting, and tag-based filtering.

## Features

- User registration and authentication
- Secure login flow with Spring Security
- Message creation with tags
- Tag-based filtering on the main feed
- PostgreSQL-backed persistence
- Mustache templates for the web UI

## Stack

- `Java 8`
- `Spring Boot 2.2.6`
- `Spring Security`
- `Spring Data JPA`
- `PostgreSQL`
- `Mustache`

## Project structure

```text
src/
├── main/
│   ├── java/
│   │   └── com/example/sweater/
│   │       ├── config/
│   │       ├── controller/
│   │       ├── domain/
│   │       ├── repos/
│   │       └── service/
│   └── resources/
│       ├── templates/
│       └── application.properties
