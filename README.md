### Intelligent Disease Prediction • Online Appointment Booking • Spring Boot • Docker • CI/CD

A full-stack healthcare web application that combines **Artificial Intelligence**, **Spring Boot**, **Cloud Deployment**, and **DevOps** to provide an intelligent clinic management solution.

</p>

---

<p align="center">

![Java](https://img.shields.io/badge/Java-17-orange?style=for-the-badge&logo=openjdk)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-4.0.5-6DB33F?style=for-the-badge&logo=springboot)
![Hibernate](https://img.shields.io/badge/Hibernate-ORM-59666C?style=for-the-badge&logo=hibernate)
![JPA](https://img.shields.io/badge/Spring_Data_JPA-Repository-blue?style=for-the-badge)
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-Template_Engine-005F0F?style=for-the-badge&logo=thymeleaf)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-7952B3?style=for-the-badge&logo=bootstrap)
![PostgreSQL](https://img.shields.io/badge/Neon-PostgreSQL-4169E1?style=for-the-badge&logo=postgresql)
![Docker](https://img.shields.io/badge/Docker-Containerized-2496ED?style=for-the-badge&logo=docker)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-CI-2088FF?style=for-the-badge&logo=githubactions)
![Render](https://img.shields.io/badge/Render-CD-46E3B7?style=for-the-badge&logo=render)
![Maven](https://img.shields.io/badge/Maven-Build-C71A36?style=for-the-badge&logo=apachemaven)

</p>

---

# 🌐 Live Demo

### 🚀 Live Application

👉 **https://ai-powered-clinic-management.onrender.com**

---

### 💻 GitHub Repository

👉 **https://github.com/Saurabh9922/ai-powered-clinic-management**

---

# 📖 Project Overview

The **AI-Powered Clinic Management System** is a modern full-stack healthcare web application developed using **Java Spring Boot** that simplifies clinic operations while integrating **Machine Learning** for intelligent disease prediction.

The application enables patients to predict possible diseases based on selected symptoms, recommends the appropriate doctor specialization, and allows users to book appointments online through an intuitive interface.

In addition to patient services, administrators can efficiently manage doctors, appointment schedules, and system data using a dedicated administration dashboard.

The project follows a clean **Spring Boot MVC Architecture**, uses **Hibernate (JPA)** for database management, is containerized with **Docker**, automatically built using **GitHub Actions (Continuous Integration)**, and deployed to the cloud using **Render** with **Neon PostgreSQL** as the production database.

This project demonstrates both **Full-Stack Java Development** and **Modern DevOps Practices**, making it suitable as an industry-oriented portfolio project.

---

# ✨ Key Features

## 👤 Patient Module

- User Registration & Login
- AI-Based Disease Prediction
- Doctor Recommendation
- View Available Doctors
- Online Appointment Booking
- Appointment History
- Appointment Cancellation
- Responsive User Dashboard

---

## 🛠 Admin Module

- Secure Admin Login
- Doctor Management
- Add / Update / Delete Doctors
- Time Slot Management
- View All Appointments
- Manage Patient Records
- System Administration Dashboard

---

## 🤖 AI Module

- Symptom-Based Disease Prediction
- Naïve Bayes Machine Learning Model
- Intelligent Doctor Recommendation
- Fast Prediction Response
- Integrated with Appointment Booking

---

## ☁ Cloud & DevOps

- Docker Containerization
- GitHub Version Control
- GitHub Actions CI Pipeline
- Automatic Deployment using Render
- Neon PostgreSQL Cloud Database
- Environment Variable Configuration
- Production Ready Deployment

---

# 🛠 Technology Stack

| Category | Technology |
|-----------|------------|
| Programming Language | Java 17 |
| Backend Framework | Spring Boot 4 |
| ORM | Hibernate & Spring Data JPA |
| Frontend | HTML, CSS, Bootstrap, Thymeleaf |
| Machine Learning | Naïve Bayes Algorithm |
| Database | Neon PostgreSQL |
| Build Tool | Maven |
| Containerization | Docker |
| Version Control | Git & GitHub |
| Continuous Integration | GitHub Actions |
| Continuous Deployment | Render |
| IDE | IntelliJ IDEA |

---

# 🏗 System Architecture

The application follows a layered **Spring Boot MVC Architecture** integrated with a Machine Learning module.

```
                 Patient / Admin
                        │
                        ▼
           Frontend (HTML + Bootstrap + Thymeleaf)
                        │
                        ▼
                 Controller Layer
                        │
                        ▼
                  Service Layer
                        │
            ┌───────────┴───────────┐
            ▼                       ▼
     Machine Learning        Repository Layer
      (Naïve Bayes)                │
                                   ▼
                         Neon PostgreSQL Database
```

---

## 📌 Architecture Diagram



<p align="center">

<img width="776" height="969" alt="image" src="https://github.com/user-attachments/assets/9c8e0759-ea6d-465d-9399-8c4f89f7f3d8" />


</p>


---

## 📖 Architecture Explanation

### 🖥 Frontend Layer

The frontend is developed using **HTML**, **CSS**, **Bootstrap**, and **Thymeleaf**, providing a responsive and user-friendly interface for both patients and administrators.

**Responsibilities**

- User Authentication
- Disease Prediction Form
- Appointment Booking
- Dashboard Pages
- Admin Interfaces

---

### 🎯 Controller Layer

The Controller layer receives HTTP requests from users and forwards them to the appropriate service methods.

**Responsibilities**

- Handle HTTP Requests
- Process User Input
- Route Web Pages
- Return Responses

---

### ⚙ Service Layer

The Service layer contains the complete business logic of the application.

**Responsibilities**

- Disease Prediction
- Appointment Booking
- Doctor Recommendation
- Time Slot Validation
- Appointment Management

---

### 🤖 Machine Learning Module

The Machine Learning module predicts diseases based on selected symptoms using the **Naïve Bayes Algorithm**.

It helps patients identify possible diseases and recommends the appropriate doctor specialization before booking an appointment.

---

### 🗄 Repository Layer

The Repository layer communicates with the database using **Spring Data JPA** and **Hibernate**.

**Responsibilities**

- CRUD Operations
- Database Queries
- Entity Management

---

### 🗃 Database Layer

The production database is hosted on **Neon PostgreSQL**.

The database stores:

- Users
- Doctors
- Diseases
- Symptoms
- Time Slots
- Appointments

---

# 🔄 Project Workflow

The following workflow illustrates how a patient interacts with the system.

```
Patient

   │

   ▼

Login / Register

   │

   ▼

Disease Prediction

   │

   ▼

Doctor Recommendation

   │

   ▼

Select Doctor

   │

   ▼

Choose Available Time Slot

   │

   ▼

Book Appointment

   │

   ▼

Appointment Confirmation

   │

   ▼

Appointment Stored in Database
```

---

## 📌 Workflow Diagram

> Save your workflow diagram as:

<p align="center">

<img width="547" height="954" alt="image" src="https://github.com/user-attachments/assets/c4fc8d34-2923-419e-a607-777ddf66a7b5" />


</p>


---

# 📂 Project Structure

The project follows a layered **Spring Boot MVC Architecture**, ensuring separation of concerns, maintainability, and scalability.

```text
src
│
├── main
│   │
│   ├── java
│   │   └── com.clinic
│   │       │
│   │       ├── config
│   │       │     ├── DataInitializer.java
│   │       │     ├── SessionInterceptor.java
│   │       │     └── WebConfig.java
│   │       │
│   │       ├── controller
│   │       │     ├── AdminController.java
│   │       │     ├── AppointmentController.java
│   │       │     ├── AuthController.java
│   │       │     ├── PageController.java
│   │       │     └── PredictionController.java
│   │       │
│   │       ├── entity
│   │       │     ├── Appointment.java
│   │       │     ├── Disease.java
│   │       │     ├── Doctor.java
│   │       │     ├── Symptom.java
│   │       │     ├── TimeSlot.java
│   │       │     └── User.java
│   │       │
│   │       ├── repository
│   │       │
│   │       ├── service
│   │       │
│   │       └── ClinicApplication.java
│   │
│   └── resources
│       ├── templates
│       ├── static
│       ├── diseases.csv
│       └── application.properties
│
└── test
```

---

## 📁 Folder Description

| Folder | Purpose |
|---------|----------|
| **config** | Contains application configuration, session handling, web configuration, and initial data loading. |
| **controller** | Handles incoming HTTP requests and returns the appropriate Thymeleaf pages or responses. |
| **service** | Contains business logic such as disease prediction, appointment booking, and doctor management. |
| **repository** | Performs database operations using Spring Data JPA. |
| **entity** | Defines database entities mapped to MySQL/PostgreSQL tables using Hibernate. |
| **templates** | Thymeleaf HTML templates rendered by Spring Boot. |
| **static** | Stores CSS, JavaScript, images, and static assets. |
| **application.properties** | Application configuration, database connection, mail settings, and server configuration. |

---

## 🏗 MVC Request Flow

```text
User

↓

Browser Request

↓

Controller

↓

Service

↓

Repository

↓

Database

↓

Repository

↓

Service

↓

Controller

↓

Thymeleaf View

↓

Browser Response
```

---

# 👥 User Roles

The application supports **Role-Based Authentication** with dedicated features for each type of user.

---

## 👤 Patient

Patients can perform the following operations:

- Register new account
- Secure login
- Predict disease using symptoms
- View recommended doctor specialization
- Book appointments
- View appointment history
- Cancel appointments

---

## 🏥 Administrator

The administrator manages the complete clinic system.

Features include:

- Secure login
- Add doctors
- Update doctor information
- Delete doctors
- Manage doctor availability
- Manage appointment slots
- Monitor appointments
- Manage system records

---

# 🗄 Database Design

The application uses a relational database managed through **Spring Data JPA** and **Hibernate ORM**.

---

## 👤 User Table

| Column | Description |
|---------|-------------|
| id | Primary Key |
| name | Full Name |
| email | Email Address |
| password | Encrypted Password |
| role | PATIENT / ADMIN |

---

## 👨‍⚕ Doctor Table

| Column | Description |
|---------|-------------|
| id | Primary Key |
| name | Doctor Name |
| specialization | Medical Specialization |

---

## 📅 Appointment Table

| Column | Description |
|---------|-------------|
| id | Appointment ID |
| patient_id | Patient Reference |
| doctor_id | Doctor Reference |
| timeslot_id | Slot Reference |
| appointment_date | Appointment Date |

---

## 🕒 TimeSlot Table

| Column | Description |
|---------|-------------|
| id | Slot ID |
| doctor_id | Doctor Reference |
| start_time | Slot Start Time |
| end_time | Slot End Time |
| booked | Booking Status |

---

## 🦠 Disease Table

| Column | Description |
|---------|-------------|
| id | Disease ID |
| name | Disease Name |
| required_specialization | Recommended Doctor Specialization |

---

## 🤒 Symptom Table

| Column | Description |
|---------|-------------|
| id | Symptom ID |
| name | Symptom Name |

---

# 🔗 Entity Relationships

```text
                 User
                   │
          One User │ Many Appointments
                   │
                   ▼
            Appointment
              ▲       ▲
              │       │
              │       │
      Doctor  │       │ TimeSlot
        │     │       │
        │     │       │
        ▼     │       ▼
     One Doctor ─── Many Slots


Disease
    ▲
    │
Many │ Many
    ▼
Symptom
```

### Relationship Summary

| Relationship | Type |
|--------------|------|
| User → Appointment | One-to-Many |
| Doctor → Appointment | One-to-Many |
| Doctor → TimeSlot | One-to-Many |
| Disease ↔ Symptom | Many-to-Many |

---

# 🤖 Disease Prediction Module

One of the key features of this application is the **AI-powered Disease Prediction System**, which predicts diseases based on patient-selected symptoms using the **Naïve Bayes Machine Learning algorithm**.

---

## Workflow

```text
Patient Login

↓

Select Symptoms

↓

Naïve Bayes Prediction

↓

Predict Disease

↓

Recommend Doctor Specialization

↓

Book Appointment
```

---

## Prediction Pipeline

### 📝 Input

- User selects symptoms from the available list.

### ⚙ Processing

- Symptoms are converted into a feature vector.
- The trained Naïve Bayes model calculates probabilities.

### 🤖 Prediction

- Disease with the highest probability is selected.

### 👨‍⚕ Recommendation

- Appropriate medical specialization is displayed.

### 📅 Next Step

- Patient can immediately book an appointment with the recommended doctor.

---

# 📅 Appointment Booking Workflow

The appointment booking process is fully integrated with the disease prediction module.

```text
User Login

↓

Disease Prediction

↓

Doctor Recommendation

↓

Select Doctor

↓

View Available Time Slots

↓

Choose Preferred Slot

↓

Confirm Appointment

↓

Appointment Saved


```

---

# 🖥 System User Interface

Below are the major interfaces implemented in the application.

---

## 🔐 Login Page

<img width="2000" height="954" alt="image" src="https://github.com/user-attachments/assets/cbe0c087-faac-4ad5-b2c5-196770b1ad4c" />


### Purpose

Provides secure authentication for Patients and Administrators.

### Features

- User Login
- Secure Authentication
- Session Management
- Dashboard Redirection

---

## 🏠 User Dashboard

<img width="2000" height="948" alt="image" src="https://github.com/user-attachments/assets/374052e3-dac0-4fd3-bbd0-bfc2bef3f7a8" />

### Purpose

Provides quick navigation to all patient features.

### Features

- Disease Prediction
- Book Appointment
- Appointment History
- User Profile

---

## 🤖 Disease Prediction

<img width="2000" height="954" alt="image" src="https://github.com/user-attachments/assets/3954d493-5ed8-449a-a0d6-67b901dbd9ee" />


### Purpose

Allows patients to select symptoms and predict diseases.

### Features

- Symptom Selection
- AI Disease Prediction
- Doctor Recommendation

---

## 📋 Disease Prediction Result

<img width="2000" height="950" alt="image" src="https://github.com/user-attachments/assets/1ef23800-cf4e-4bf4-8b68-335192b42f24" />


### Purpose

Displays prediction results generated by the Machine Learning model.

### Features

- Predicted Disease
- Recommended Specialist
- Healthcare Suggestions

---

## 📅 Appointment Booking

<img width="2000" height="944" alt="image" src="https://github.com/user-attachments/assets/74bb2803-1b9f-42ea-b1c5-00f6c89eeb47" />


### Purpose

Allows users to schedule appointments with available doctors.

### Features

- Doctor Selection
- Available Slot Selection
- Appointment Booking

---

## ✅ Appointment Confirmation

<img width="2000" height="953" alt="image" src="https://github.com/user-attachments/assets/e03c2704-795d-4134-b105-de9622ea6d85" />


### Purpose

Confirms successful appointment booking.

### Features

- Booking Confirmation
- Appointment Details
- Appointment History

---

## 🛠 Admin Dashboard

<img width="2000" height="953" alt="image" src="https://github.com/user-attachments/assets/b1f67c8b-62ea-4813-af67-0c7fc3c296fd" />


### Purpose

Provides complete administrative control.

### Features

- Doctor Management
- Appointment Monitoring
- Dashboard Statistics
- System Administration




---

---

# 🚀 Local Installation

Follow these steps to run the project on your local machine.

## Prerequisites

Ensure the following software is installed:

| Software | Version |
|----------|----------|
| Java | 17 or above |
| Maven | 3.8+ |
| Git | Latest |
| PostgreSQL | 15+ (or MySQL if using local development) |
| Docker | Latest (Optional) |
| IntelliJ IDEA / VS Code | Latest |

---

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/Saurabh9922/ai-powered-clinic-management.git
```

```bash
cd ai-powered-clinic-management
```

---

## 2️⃣ Configure Database

Create a PostgreSQL (Neon) or MySQL database.

Example:

```
Database Name : clinic_db
Username      : postgres
Password      : your_password
```

---

## 3️⃣ Configure Environment Variables

Create a `.env` file or configure environment variables.

```
DB_URL=jdbc:postgresql://localhost:5432/clinic_db
DB_USERNAME=postgres
DB_PASSWORD=password

```

---

## 4️⃣ Build the Project

```bash
mvn clean install
```

---

## 5️⃣ Run the Application

```bash
mvn spring-boot:run
```

or

```bash
java -jar target/clinic-management.jar
```

---

## 6️⃣ Open in Browser

```
http://localhost:8080
```

---

# ⚙ Configuration

The application uses environment variables to keep sensitive information secure.

| Variable | Description |
|-----------|-------------|
| DB_URL | PostgreSQL/MySQL JDBC URL |
| DB_USERNAME | Database Username |
| DB_PASSWORD | Database Password |
| MAIL_USERNAME | Gmail Address |
| MAIL_PASSWORD | Gmail App Password |
| SERVER_PORT | Server Port |

Example:

```properties
spring.datasource.url=${DB_URL}
spring.datasource.username=${DB_USERNAME}
spring.datasource.password=${DB_PASSWORD}

spring.mail.username=${MAIL_USERNAME}
spring.mail.password=${MAIL_PASSWORD}
```

---

# 🐳 Docker

Docker is used to package the application into a portable container.

## Build Docker Image

```bash
docker build -t clinic-management .
```

---

## Run Docker Container

```bash
docker run -p 8080:8080 clinic-management
```

---

## Verify Running Container

```bash
docker ps
```

---

# ☁ Deployment (Render + Neon PostgreSQL)

The application is deployed using **Render** with **Neon PostgreSQL** as the cloud database.

---

## Deployment Architecture

```text
Developer

      │

      ▼

GitHub Repository

      │

      ▼

GitHub Actions (CI)

      │

      ▼

Docker Image Build

      │

      ▼

Render Deployment

      │

      ▼

Spring Boot Application

      │

      ▼

Neon PostgreSQL Database
```

---

## Deployment Steps

### Step 1

Push code to GitHub.

```bash
git add .

git commit -m "Production Deployment"

git push origin main
```

---

### Step 2

Render automatically detects changes from GitHub.

---

### Step 3 – Continuous Integration (GitHub Actions)

Whenever code is pushed to the **main** branch, GitHub Actions automatically starts the Continuous Integration (CI) workflow.

The workflow performs the following tasks:

- ✔ Checkout the latest source code from the GitHub repository.
- ✔ Set up the Java 17 environment.
- ✔ Restore Maven dependencies from cache for faster builds.
- ✔ Compile the Spring Boot application.
- ✔ Package the application into an executable JAR file using Maven (`mvn clean package -DskipTests`).
- ✔ Verify that the build is successful.

At the end of this stage, a production-ready JAR file is generated.

---

### Step 4 – Continuous Deployment (Render)

After the GitHub Actions workflow completes successfully, Render automatically detects the latest commit from the GitHub repository.

Render then performs the following deployment steps:

- ✔ Detect the latest commit pushed to the **main** branch.
- ✔ Read the project's `Dockerfile`.
- ✔ Build a new Docker image containing the Spring Boot application.
- ✔ Create a new Docker container from the image.
- ✔ Start the Spring Boot application inside the container.
- ✔ Load all configured environment variables.
- ✔ Establish a secure connection to the Neon PostgreSQL database.
- ✔ Deploy the latest version of the application to the production environment.

The updated application becomes available automatically without requiring any manual deployment.
---

### Step 5

Application starts automatically.

---

### Step 6

Connects securely to Neon PostgreSQL.

---

# 🚀 CI/CD Pipeline

The project follows an automated Continuous Integration and Continuous Deployment (CI/CD) pipeline using GitHub Actions, Docker, Render, and Neon PostgreSQL.

Every push to the main branch automatically triggers the build process, packages the application, and deploys the latest version to the cloud.
## 📌 CI/CD Pipeline Architecture

<p align="center">
<img width="459" height="1542" alt="2 cicd pipline" src="https://github.com/user-attachments/assets/eefa75c0-04b8-4e06-9f8c-d3dccaa9d68c" />
</p>

---

## 🔄 CI/CD Pipeline Execution

The CI/CD workflow is fully automated and is triggered whenever changes are pushed to the `main` branch.

### Continuous Integration (CI)

1. Developer pushes code to GitHub.
2. GitHub Actions starts automatically.
3. The repository is checked out.
4. Java 17 is installed.
5. Maven dependencies are restored from cache.
6. The Spring Boot project is compiled.
7. An executable JAR file is generated.

### Continuous Deployment (CD)

1. Render detects the latest commit.
2. Render builds the Docker image.
3. A new application container is created.
4. The application starts automatically.
5. Environment variables are loaded.
6. The application connects securely to Neon PostgreSQL.
7. The latest version becomes available to users.
---

## CI Process

✔ Checkout Repository

✔ Setup Java 17

✔ Restore Maven Cache

✔ Compile Spring Boot Project

✔ Package Executable JAR (mvn clean package -DskipTests)

✔ Build Completed Successfully

---

## CD Process

✔ Detect GitHub Push

✔ Trigger Render Deployment

✔ Pull Latest Source Code

✔ Build Docker Container

✔ Start Spring Boot Application

✔ Connect to Neon Database

✔ Production Deployment Completed

---

# 📊 GitHub Actions Pipeline

The workflow file is located at:

```
.github/workflows/ci.yml
```

Pipeline Stages

| Stage | Description |
|--------|-------------|
| Checkout | Download Repository |
| Setup Java | Install JDK 17 |
| Cache Maven | Speed up Build |
| Install Dependencies | Download Libraries |
| Build | Compile Project |
| Test | Execute Unit Tests |
| Package | Generate Executable JAR |
| Docker Build | Build Docker Image |
| Deployment | Render Automatically Deploys |

---

## Pipeline Overview

```text
Git Push

↓

Checkout

↓

Java Setup

↓

Maven Cache

↓

Build

↓

Test

↓

Package

↓

Docker Build

↓

Render Deployment

↓

Application Live
```

---

# 📈 Future Improvements

Planned enhancements include:

- 📱 Android & iOS Mobile Application
- 💳 Online Payment Gateway Integration
- 📹 Video Consultation (Telemedicine)
- 🔔 SMS Notifications
- 📅 Google Calendar Integration
- 📊 Analytics Dashboard
- 📂 Electronic Health Records (EHR)
- 🤖 Deep Learning-based Disease Prediction
- ☸ Kubernetes Deployment
- ☁ AWS / Azure / Google Cloud Migration
- 📈 Monitoring with Prometheus & Grafana
- 🔍 Elasticsearch Logging
- 🔐 OAuth2 / JWT Authentication
- 📦 Microservices Architecture

---

# 🤝 Contributing

Contributions are welcome!

### Steps

1. Fork this repository

2. Create a new branch

```bash
git checkout -b feature/YourFeature
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push your branch

```bash
git push origin feature/YourFeature
```

5. Open a Pull Request

---

# 📜 License

This project is licensed under the **MIT License**.

Feel free to use, modify, and distribute this project for educational and personal purposes.

For commercial use, please review the license terms.

# 👨‍💻 Author

**Saurabh Mapari**

M.Tech Computer Engineering  
Pune Institute of Computer Technology (PICT)

### Connect with Me

- 💼 LinkedIn: https://linkedin.com/in/saurabhmapari
- 📧 Email:  saurabhmapari9922@gmail.com
- 🐙 GitHub: https://github.com/Saurabh9922


---

## ⭐ Support the Project

If you found this project useful:

⭐ Star this repository

🍴 Fork it

📢 Share it

🤝 Contribute

---

<p align="center">

Made with ❤️ by **Saurabh Mapari**

</p>
