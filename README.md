# 👋 Hi, I'm Andres Marquez  

Welcome to my GitHub!  
Here you’ll find a collection of projects that represent my learning journey in **.NET**, **Clean Architecture**, **Microservices**, and beyond.  
I focus on building professional, well-structured applications while continuously improving my skills in modern technologies.

---

## 📁 Featured Projects

### 1. ReportManager.CleanArchitecture.CrudOnly
> A Clean Architecture project that implements basic CRUD operations using ASP.NET Core Web API and Entity Framework Core.

- **Tech Stack:** ASP.NET Core 8, Entity Framework Core, SQL Server  
- **Architecture:** Clean Architecture (Domain, Application, Infrastructure, WebAPI)  
- **Highlights:**  
  - Clear separation of concerns  
  - Repository & Unit of Work patterns  
  - Clean API controllers with dependency injection  
- **Potential Improvements:** Authentication and frontend integration in future iterations  

🔗 [View Repository](https://github.com/andresmarz/ReportManager.CleanArchitecture.CrudOnly)

---

### 2. ReportManager.CleanArchitecture.CrudAndJWT
> An extended version of the previous project, adding secure authentication and authorization using JWT.

- **Tech Stack:** ASP.NET Core 8, Entity Framework Core, SQL Server  
- **Authentication:** ASP.NET Identity with JWT (JSON Web Tokens)  
- **Architecture:** Clean Architecture  
- **Highlights:**  
  - Secure login with token-based authentication  
  - Role-based access control  
  - Protected CRUD endpoints  

🔗 [View Repository](https://github.com/andresmarz/ReportManager.CleanArchitecture.CrudAndJWT)

---

### 3. MicroservicesApp.TwoServicesWithCleanCRUDs
> Two microservices (`CatalogService` and `OrderingService`) built with **ASP.NET Core 8** using **Clean Architecture**.  
Each service implements its own CRUD operations and database.

- **Tech Stack:** ASP.NET Core 8, Entity Framework Core, SQL Server  
- **Highlights:** Independent microservices with isolated databases and clean separation of concerns  

🔗 [View Repository](https://github.com/andresmarz/MicroservicesApp.TwoServicesWithCleanCRUDs)

---

### 4. MicroservicesApp.RESTCommunicationBetweenTwoMicroservices
> Extends the previous step by enabling **REST communication** between microservices.  
The Ordering service queries product data from the Catalog API.

- **Tech Stack:** ASP.NET Core 8, Entity Framework Core, HttpClient  
- **Highlights:** Demonstrates synchronous communication between microservices  

🔗 [View Repository](https://github.com/andresmarz/MicroservicesApp.RESTCommunicationBetweenTwoMicroservices)

---

### 5. MicroservicesApp.DockerizedRESTCommunicationBetweenTwoMicroservices
> Dockerized version of the REST communication project.  
Both services and their databases run inside containers orchestrated with **Docker Compose**.

- **Tech Stack:** ASP.NET Core 8, Entity Framework Core, SQL Server, Docker & Docker Compose  
- **Highlights:** REST communication inside a Docker network, fully containerized microservices  

🔗 [View Repository](https://github.com/andresmarz/MicroservicesApp.DockerizedRESTCommunicationBetweenTwoMicroservices)

---

### 6. MicroservicesApp.DockerComposeAndRabbitMQ
> Adds **asynchronous communication** between services using **RabbitMQ**.  
The Catalog and Ordering services publish and consume events through a message broker.

- **Tech Stack:** ASP.NET Core 8, Entity Framework Core, SQL Server, Docker & Docker Compose, RabbitMQ, MassTransit  
- **Highlights:** Event-driven architecture with RabbitMQ, REST communication preserved as fallback  

🔗 [View Repository](https://github.com/andresmarz/MicroservicesApp.DockerComposeAndRabbitMQ)

---

## 🚀 Next Steps
I’m expanding my knowledge into:  
- **Python** for AI and Data Science  
- **Azure & CI/CD pipelines** for cloud deployments  
- **Kubernetes** for container orchestration  

Stay tuned for upcoming repositories!  

---

## 📫 Connect
- GitHub: [@andresmarz](https://github.com/andresmarz)  
- LinkedIn: https://www.linkedin.com/in/gustavomarquezzuleta/
