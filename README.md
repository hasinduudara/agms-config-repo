# AGMS Configuration Repository ⚙️

## About This Repository
This repository serves as the centralized configuration source for the **Automated Greenhouse Management System (AGMS)**. [cite_start]It is connected to the Spring Cloud Config Server to manage and provide externalized properties for all distributed microservices in the system[cite: 176].

[cite_start]By keeping these configurations in a single Git repository, the microservices can dynamically fetch their specific settings (like database credentials, server ports, and Eureka URLs) during startup without hardcoding them into the application code[cite: 176, 177].

## 📂 Configuration Files

* **`api-gateway.yml`**: Contains routing rules, CORS configurations, and JWT security settings for the Spring Cloud API Gateway.
* **`zone-service.yml`**: Contains PostgreSQL database credentials, Hibernate settings, and Eureka client configurations for the Zone Management Service.
* **`automation-service.yml`**: Configuration properties for the Node.js/TypeScript Automation Rule Engine.
* **`crop-service.yml`**: Contains MongoDB connection URI and configurations for the Node.js Crop Inventory Service.

## 👨‍💻 Author

* **Name:** M. Hasindu Udara
* **Email:** [hasiduudara@gmail.com](mailto:hasiduudara@gmail.com)
* **LinkedIn:** [https://www.linkedin.com/in/hasindu-udara/](https://www.linkedin.com/in/hasindu-udara/)
* **Portfolio:** [https://www.hasinduudara.me/](https://www.hasinduudara.me/)