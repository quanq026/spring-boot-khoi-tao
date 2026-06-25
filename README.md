# Product Management - Spring Boot Project

## Mục tiêu
Khởi tạo dự án Spring Boot với Spring Initializr, hiểu cấu trúc Maven project.

## Cấu trúc
```
product-management/
├── pom.xml                         # Maven config, Spring Boot 3.4.1, Spring Web
├── src/main/java/
│   └── com/example/productmanagement/
│       └── ProductManagementApplication.java  # @SpringBootApplication
└── src/main/resources/
    └── application.properties      # server.port=8080
```

## Yêu cầu
- Maven project
- Java 17
- Spring Boot 3.4.1
- Group: com.example, Artifact: product-management
- Dependency: Spring Web

## Chạy
```bash
mvn spring-boot:run
# Console log: Tomcat started on port 8080
```
