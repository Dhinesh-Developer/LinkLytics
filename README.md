# 🔗 LinkLytics – Intelligent URL Shortener with Analytics

**LinkLytics** is a full-stack web application that allows users to create, manage, and analyze shortened URLs. Built with modern Java-based backend and React frontend, this platform is a scalable, secure, and analytics-driven solution inspired by services like Bitly and TinyURL.

---

## 🚀 Tech Stack

### 🔧 Backend
- **Spring Boot** (RESTful API development)
- **Spring Security** (JWT, OAuth-based authentication)
- **Hibernate & JPA** (Object-Relational Mapping)
- **MySQL** (Relational Database)

### 🌐 Frontend
- **React.js** (Component-based UI rendering)
- **Bootstrap** (Responsive styling)

### ☁️ DevOps
- **Docker** (Containerization and local deployment)
- **Docker Hub** (Image hosting)
- **AWS (Basics)** – For potential cloud deployment

---

## 🛠️ Features

- 🔗 **URL Shortening** – Converts long URLs into short, unique links using hashing techniques.
- 📊 **Real-Time Analytics** – Tracks click counts and user interaction.
- 🧑‍💻 **Authentication** – Implements secure login using:
  - **JWT (JSON Web Tokens)** for session-based authentication
  - **GitHub OAuth** for social login
- 🧱 **Modular Architecture** – Clean MVC-based project structure.
- 🐳 **Dockerized Deployment** – Easily run the app locally using Docker.

---

## 🧠 System Design & Architecture

### ✔️ Key Concepts Implemented

- **Single Responsibility Principle (SRP)**  
  Each class and layer (Controller, Service, Repository) handles a single function — improving maintainability.

- **MVC Design Pattern**  
  Followed clean separation of concerns across:
  - Controller (API endpoints)
  - Service (business logic)
  - Repository (DB access via JPA/Hibernate)

- **OOPS Concepts**  
  Applied inheritance, abstraction, encapsulation, and polymorphism across service and entity layers.

---

## 💻 DSA Concepts

- **Hashing Algorithm**  
  Used to generate unique short links from long URLs efficiently — ensuring collision handling and uniqueness.

- **Collections API**  
  Java Collections (e.g., `Map`, `List`) were used to manage user sessions, analytics data, and cache.

---

## 🧬 ORM with Hibernate + JPA

- Defined entity relationships (OneToMany, ManyToOne) for:
  - User ↔ Links
  - Links ↔ Analytics
- Used annotations for schema generation and data consistency in MySQL.

---

## 🐳 Docker Deployment

### Run Locally with Docker

```bash
# Build Docker image
docker build -t link-lytics .

# Run container
docker run -p 8080:8080 link-lytics
🔐 Authentication
JWT – Secures private endpoints with token-based access.

GitHub OAuth – Allows GitHub-based sign-in with secure token exchange.


LinkLytics/
│
├── backend/
│   ├── src/main/java/com/linklytics/
│   │   ├── controller/
│   │   ├── service/
│   │   ├── repository/
│   │   ├── model/
│   │   └── security/
│
├── frontend/
│   └── src/components/
│       ├── CreateLink.jsx
│       ├── Dashboard.jsx
│       └── Login.jsx
│
├── Dockerfile
├── application.properties
└── README.md


📌 Future Enhancements
🔍 Search/filter functionality for links

🌍 Global click heatmaps

📤 Export analytics in CSV

📱 Mobile responsiveness


---

## 🔗 Live Preview (Optional)
*Coming soon on Docker/AWS (based on your deployment status)*

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 🙋‍♂️ Author

- **Dhinesh Kumar M**  
  [LinkedIn](https://www.linkedin.com/in/dhineshkumar-m-b75b1a283/) | [GitHub](https://github.com/Dhinesh-Developer) | [Portfolio](https://dhinesh3369.neocities.org/DhineshKumar/portfolio/dk)

---


