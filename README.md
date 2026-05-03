# Spring Boot User Management API

A production-style backend REST API built with Spring Boot, MongoDB, and Docker. Includes interactive API documentation using OpenAPI (Swagger).

## 🚀 Tech Stack

* Java 21
* Spring Boot
* MongoDB
* Docker
* OpenAPI (Swagger)

## 📌 Features

* Full CRUD operations
* RESTful API design
* MongoDB integration
* Dockerized database
* Interactive API documentation

## 🧪 Run the project

### Start MongoDB (Docker)

docker run -d -p 27017:27017 --name mongodb mongo

### Run application

mvn spring-boot:run

### Swagger UI

http://localhost:8080/swagger-ui/index.html

## 📸 API Preview

<img width="2728" height="1578" alt="image" src="https://github.com/user-attachments/assets/e6dabba2-4add-4069-80d4-fed22b151772" />

## 🧪 Sample Request

POST /users

{
  "name": "Mark",
  "role": "Engineer"
}

<img width="2010" height="1462" alt="image" src="https://github.com/user-attachments/assets/03683e7d-8d6d-4511-b19f-788a6b3090a3" />

## 🧪 How to Run Locally
No external setup needed except Docker and Java

1. Clone the repository
git clone https://github.com/YOUR-USERNAME/springboot-user-api.git

2. Start MongoDB (Docker)
docker run -d -p 27017:27017 --name mongodb mongo

3. Run the application
mvn spring-boot:run

4. Open Swagger UI
http://localhost:8080/swagger-ui/index.html

## 💡 Author

Dave Andrew Ong
