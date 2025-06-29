# Blog App APIs

A simple and modular backend API for a Blog Application, built with **Java Spring Boot**, supporting blog post creation, editing, deletion, and user management.

## Features

* Create, Read, Update, Delete (CRUD) for blog posts
* User registration and authentication
* Role-based access control
* JWT token-based authentication
* MySQL database integration

## Tech Stack

* **Backend:** Java Spring Boot
* **Database:** MySQL
* **Authentication:** JWT (JSON Web Token)
* **Tools:** Swagger for API testing, Spring Data JPA for ORM

## Getting Started

### Prerequisites

* [Java JDK 17+](https://www.oracle.com/java/technologies/javase-downloads.html)
* [Maven](https://maven.apache.org/)
* [MySQL](https://www.mysql.com/)

### Setup Instructions

1. **Clone the repository**

```bash
https://github.com.mcas.ms/shubham-thorve/blog_app_apis
```

2. **Navigate to the project directory**

```bash
cd blog_app_apis
```

3. **Configure MySQL database**
   Update `application.properties` with your MySQL credentials and JWT secret.

4. **Run the Application**

```bash
mvn spring-boot:run
```

5. **Test with Swagger**
   Navigate to `http://localhost:8080/swagger-ui/` to explore and test all endpoints.

## API Endpoints

### Auth

* `POST /api/auth/register` — Register a new user
* `POST /api/auth/login` — User login

### Blogs

* `GET /api/blogs` — Get all blogs
* `GET /api/blogs/{id}` — Get blog by ID
* `POST /api/blogs` — Create new blog
* `PUT /api/blogs/{id}` — Update blog
* `DELETE /api/blogs/{id}` — Delete blog

## Contribution

Feel free to fork the repo, raise issues, or contribute via pull requests.

## License

This project is open-source and available under the [MIT License](LICENSE).
