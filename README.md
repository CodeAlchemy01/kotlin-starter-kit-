
# Kotlin DDD Starter Kit

## Project Overview
The **Kotlin DDD Starter Kit** is an open-source project designed as a foundation or inspiration for building **Domain-Driven Design (DDD)** applications in Kotlin. This sample project demonstrates the application of DDD principles using modern technologies and tools, focusing on a didactic domain of maintaining orders. It leverages **CQRS (Command Query Responsibility Segregation)** to handle commands and queries separately, ensuring a scalable and modular architecture.

> **Note**: This is a conceptual implementation and not intended to be production-ready.

---

## Tech Stack

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Axon Framework](https://img.shields.io/badge/Axon%20Framework-005F8F?style=for-the-badge&logo=axon&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

---

## Key Features
- **CQRS Architecture**: Separates command and query responsibilities for better scalability and maintainability.
- **Domain-Driven Design**: Implements core DDD principles with clear separation between domain, application, and infrastructure layers.
- **Order Management**: Includes operations like creating orders, adding/removing products, and processing payments.
- **Event-Driven Architecture**: Utilizes Axon Framework for managing events and handling side effects like shipping notifications.
- **RabbitMQ Integration**: Configures persistent messaging for handling commands and events reliably.
- **Postman API Requests**: Pre-configured Postman collection to trigger all application operations.
- **Gradle Build**: Simplified project setup and testing using Gradle scripts.

---

## Snapshots

![WhatsApp Image 2024-12-05 at 12 04 58 PM](https://github.com/user-attachments/assets/480a9aa0-a8b5-452a-9921-4a8c5585de16)
![WhatsApp Image 2024-12-05 at 12 05 21 PM](https://github.com/user-attachments/assets/6309a1ff-a3b8-4fb6-84eb-08fcd6e7c725)


### CQRS Workflow  
Command and query processing is divided into two distinct paths for clarity and performance.


### RabbitMQ Integration  
Persistent messaging setup for reliable event handling.

### Postman Requests  
Easily trigger application operations using pre-configured Postman JSON.

---

## My Contributions
- Designed and implemented the **CQRS architecture**, ensuring clean separation of responsibilities.
- Integrated the **Axon Framework** for seamless command and event handling.
- Configured **RabbitMQ** for persistent message queues and exchanges.
- Authored modular and scalable layers: **Domain**, **Application**, and **Infrastructure**.
- Enhanced developer experience by adding pre-configured **Postman collections** and robust Gradle scripts.
- Outlined future enhancements such as JPA repositories, Swagger UI integration, and Dockerized setup for streamlined development.

---

## Impact
The **Kotlin DDD Starter Kit** serves as a comprehensive foundation for developers looking to implement Domain-Driven Design with modern tools. By providing a clear architecture, CQRS integration, and robust event-handling capabilities, it significantly accelerates the development of scalable and maintainable systems. This project promotes best practices, ensuring that teams can focus on solving business problems with confidence and clarity.
