# Interprise Dealership
Study project for the creation of a car and motorcycle rental dealership

## Technologies Used

### Backend

- **Java 17**
- **Spring Boot**
- **Spring Security**
- **JPA / Hibernate**
- **MySQL**
- **Gradle**
- **Swagger**

### Frontend

- **React**
- **React Native**

## Project Structure - Backend

### Main Packages

### Entities

## Gradle dependencies
Make sure that the `build.gradle`

```gradle
implementation 'org.springframework.boot:spring-boot-starter-data-jpa'
implementation 'org.springframework.boot:spring-boot-starter-web'
implementation group: 'org.springdoc', name: 'springdoc-openapi-starter-webmvc-ui', version: '2.6.0'
implementation group: 'org.springframework.boot', name: 'spring-boot-starter-security', version: '3.3.1'
runtimeOnly 'com.mysql:mysql-connector-j'
runtimeOnly 'org.postgresql:postgresql'
testImplementation 'org.springframework.boot:spring-boot-starter-test'
testRuntimeOnly 'org.junit.platform:junit-platform-launcher'
```

## Project Structure - Frontend
