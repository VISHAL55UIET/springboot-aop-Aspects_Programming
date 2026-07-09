# 🚀 Spring Boot AOP - Aspect Oriented Programming

A production-style Spring Boot project demonstrating the implementation of **Aspect-Oriented Programming (AOP)** to separate cross-cutting concerns such as logging and validation from the core business logic.

This project showcases how Spring AOP can improve code maintainability, readability, and modularity using custom annotations and reusable aspects.

---

## 📌 Features

- ✅ Aspect-Oriented Programming using Spring AOP
- ✅ Logging with Before Advice
- ✅ Logging with Around Advice
- ✅ Method Execution Time Monitoring
- ✅ Request Validation using Aspect
- ✅ Custom Annotation (`@MyLogging`)
- ✅ Separation of Business Logic and Cross-Cutting Concerns
- ✅ Clean Layered Architecture

---

## 🛠 Tech Stack

| Technology | Version |
|------------|----------|
| Java | 17+ |
| Spring Boot | 3.x |
| Spring AOP | Latest |
| Maven | 3.x |
| IntelliJ IDEA | IDE |
| Git & GitHub | Version Control |

---

## 📂 Project Structure

```
src
├── main
│   ├── java
│   │   └── com.codingshuttle.aopApp
│   │       ├── aspects
│   │       │   ├── LoggingAspect.java
│   │       │   ├── LoggingAspectV2.java
│   │       │   ├── ValidationAspect.java
│   │       │   └── MyLogging.java
│   │       │
│   │       ├── services
│   │       │   ├── ShipmentService.java
│   │       │   └── impl
│   │       │       └── ShipmentServiceImpl.java
│   │       │
│   │       └── AopAppApplication.java
│   │
│   └── resources
│       └── application.properties
```

---

## 📖 Concepts Covered

### Before Advice

Executes before the target method.

Example:

- Logging method name
- Printing arguments
- Validation checks

---

### Around Advice

Wraps the target method execution.

Used for:

- Measuring execution time
- Logging request and response
- Exception handling

---

### Custom Annotation

```java
@MyLogging
```

Only methods annotated with `@MyLogging` are intercepted by the custom logging aspect.

---

### Validation Aspect

Demonstrates how input validation can be handled separately from the business logic using AOP.

---

## ▶️ Running the Project

### Clone Repository

```bash
git clone https://github.com/VISHAL55UIET/springboot-aop-Aspects_Programming.git
```

### Navigate to Project

```bash
cd springboot-aop-Aspects_Programming
```

### Build

```bash
mvn clean install
```

### Run

```bash
mvn spring-boot:run
```

The application starts on

```
http://localhost:8080
```

---

## 📸 What This Project Demonstrates

- Aspect-Oriented Programming
- Cross-Cutting Concerns
- Logging
- Validation
- Custom Annotations
- Spring Boot Best Practices

---

## 🎯 Learning Outcomes

By exploring this project, you will understand:

- What is Spring AOP?
- Why AOP is needed?
- Pointcuts
- Join Points
- Advice Types
- Around Advice
- Before Advice
- Custom Annotations
- Code Reusability
- Clean Architecture

---

## 🤝 Contributing

Contributions are welcome.

If you'd like to improve the project:

1. Fork the repository
2. Create a new feature branch
3. Commit your changes
4. Open a Pull Request

---

## 👨‍💻 Author

**Vishal Singh**

- GitHub: https://github.com/VISHAL55UIET
- LinkedIn: https://www.linkedin.com/in/vishal-singh-5b052828a/

---

## ⭐ Support

If you found this project helpful,

⭐ Star this repository.

It helps others discover the project and motivates further development.

---

## 📄 License

This project is intended for learning and educational purposes.
