<div id="header" align="center">
  <img src="https://media.giphy.com/media/paTz7UZbPfTZFRYnnB/giphy.gif" width="200"/>
  
<a href='https://t.me/asirazetdinova' target="_blank">![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)</a>
<a href="mailto:allina.damirovna@gmail.com" target="blank">![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)</a>

  <br>
</div>


<h1 align="center">Hi there, I'm Alina</a> 
<img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/></h1>
<h3 align="center">Java developer and just a nice person</h3>


### Education:
- **<a href='https://kpfu.ru' target="_blank">Kazan Federal University</a>** Information Systems and Technologies, 4th year
- **<a href="https://education.tbank.ru/academy/backend/">T-Bank</a>** Java, SRE
- **<a href="https://practicum.yandex.ru/">Yandex</a>** Python
- **<a href="https://21-school.ru/">Sberbank</a>** C, Linux 
<!-- ### BIO :notebook:	 -->

##

### Work experience (2 years 9 months):
**SK Sfera** | Programmer (July 2024 - Present) <br> 
Developing Java microservices for document management, writing technical documentation for code

**<a href='https://3.shkolkovo.online/Shkolkovo' target="_blank">Shkolkovo</a>** | Programming Curator (March 2023 - July 2024) <br>
Teaching algorithms, code review: improving code readability and algorithm efficiency

##

### Technical skills:
<p align="left">
Programming languages: Java, Python <br>
Tools: Spring Boot, API, JWT, CI/CD, Kubernetes, Docker, Postman, Linux, Nginx, Resilience4j, JUnit, Mockito, Apache Kafka, Sage, ELK <br>
Databases: PostgreSQL, SQLite, MicrosoftSQL, Redis, Flyway, Liquibase <br>
</p>

##

### Main projects

**Tinkoff | Microservice application for tracking updates on StackOverflow and GitHub** 
* Telegram Bot on **Java** using **Spring Boot** interacts with users. **Telegram Bot API** supports commands, finite state machines using **Spring State Machine**, and notification modes
* Scrapper multithreaded scheduler on Spring Boot with custom HTTP clients on **Spring WebClient** for GitHub and StackOverflow APIs, and with **Resilience4j** retry policy (Retry, Circuit Breaker)
* Asynchronous interaction between **Apache Kafka** and **HTTP** services. Dead Letter Queues and caching are implemented in **Redis** using **Spring Data Redis**.
* Database access is configured using **PostgreSQL** and **JPA/Hibernate**, and **Liquibase** is used to manage migrations.
* **Prometheus** is configured to collect **JVM** metrics, **RED** metrics collection is configured in Prometheus, with visualization using **Grafana** and **Micrometer**.
* Services are in isolated **Docker** containers with **Kubernetes** orchestration and local launch with **Docker Compose**. **Swagger** is used for documentation.
* The code is covered by tests using **Testcontainers** for reliability.

**MTS | Distributed system for managing bank deposits** 
* Microservice architecture in **Java** using **Spring Boot**, service interaction provided by **Spring RestTemplate**
* Central hub eureka-server based on **Eureka** detects and registers microservices
* Microservice customer-service stores customer data and generates **JWT** tokens for authentication using **Spring Security**
* Microservice aggregator-service as an **API Gateway** on **Spring Cloud Gateway** validates **JWT** tokens before routing
* Microservices deposit-service and account-service handle deposit and account operations, respectively
* Data is stored in **PostgreSQL**, and **Flyway** is used to manage migrations.
* The code is covered by tests using **JUnit** and **Mockito** for reliability.

**Yandex | Social network for cooks** 
* Backend implemented in **Python** with **Django** and **Django REST Framework**, including CRUD operations and authentication with **JWT** tokens and **Djoser**
* Frontend is an SPA on **React** with JavaScript, Bootstrap styling, HTML, and CSS for the interface.
* **PostgreSQL** database for prod and **SQLite** for dev and test, migration management with **Django ORM**.
* Deployment with **Nginx** as a reverse proxy and **Gunicorn** for the WSGI server. Services in isolated **Docker** containers with **Docker Compose** orchestration.
* The code is covered by **Pytest** tests and **Flake8**, **Ruff**, **Black**, and **Mypy**
* **CI/CD** using **GitHub Actions** for test automation, building on Docker Hub, and deployment with notifications via **Telegram Bot API**. Added **Django Debug Toolbar**, **Postman**, and **Swagger** tools for debugging and documentation

<!--
**Sirazetdinova/Sirazetdinova** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
