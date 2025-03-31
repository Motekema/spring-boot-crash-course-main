# Spring Boot Crash Course

## 📌 Overview
This repository contains code and resources for a Spring Boot crash course. It's designed to help developers quickly get up to speed with core Spring Boot concepts through practical examples.

## 🚀 Prerequisites
Before running this project, ensure you have:
- Java JDK 11 or later
- Maven 3.6+
- Your favorite IDE (IntelliJ IDEA recommended)
- Basic Java knowledge

## ⚡ Quick Start

```bash
# Clone the repository
git clone https://github.com/yourusername/spring-boot-crash-course-main.git

# Navigate to project directory
cd spring-boot-crash-course-main

# Build and run
mvn spring-boot:run

# 🏗️ Project Structure

src/
├── main/
│   ├── java/
│   │   └── com/example/demo/
│   │       ├── controller/       # REST controllers
│   │       ├── model/            # Data models
│   │       ├── repository/       # Data repositories
│   │       ├── service/          # Business logic
│   │       └── DemoApplication.java
│   └── resources/
│       ├── static/               # Static content
│       ├── templates/            # Thymeleaf templates
│       └── application.properties
pom.xml

 # 🔥 Key Features

✅ Spring Boot auto-configuration

✅ REST API development

✅ Spring Data JPA with H2

✅ Dependency Injection

✅ Spring MVC

✅ Exception handling

✅ Testing (JUnit + Mockito)

✅ Spring Security basics

# ⚙️ Configuration

server.port=8080

# H2 Database
spring.datasource.url=jdbc:h2:mem:testdb
spring.h2.console.enabled=true
spring.h2.console.path=/h2-console

# 🌐 API Endpoints


Method	Endpoint	Description
GET	/api/items	Get all items
GET	/api/items/{id}	Get item by ID
POST	/api/items	Create new item
PUT	/api/items/{id}	Update item
DELETE	/api/items/{id}	Delete item

# 🧪 Testing

mvn test

# 🛠️ H2 Database Console

Access at: http://localhost:8080/h2-console
Credentials:

JDBC URL: jdbc:h2:mem:testdb

Username: sa

Password: password

🤝 Contributing
Pull requests welcome! For major changes, please open an issue first.

# 📜 License


Key GitHub Markdown features included:
- Proper code blocks with language specification
- Emoji headers for better visual scanning
- Table formatting for API endpoints
- Clear section hierarchy with ## and ### headers
- Text formatting for emphasis
- Consistent code block styling
- Proper escaping of special characters

The formatting will render beautifully on GitHub with proper syntax highlighting and organization.
