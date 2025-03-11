# CustomWebAppJava
# Blog Application

## Table of Contents

1. [Screenshots](#screenshots)
2. [Technologies](#technologies)  
3. [Features](#features)  
4. [Installation & Setup](#installation--setup)  
5. [API Endpoints](#api-endpoints)  
6. [Code Structure](#code-structure)  
7. [Security Features](#security-features)  
8. [Frontend Details](#frontend-details)  


A custom blog platform built with Java Spring Boot, MongoDB, and Thymeleaf template engine.

## Screenshots
### 1
![1](screenshots/1.png)
### 2
![2](screenshots/2.png)
### 3
![3](screenshots/3.png)
### 4
![4](screenshots/4.png)
### 5
![5](screenshots/5.png)
### 6
![6](screenshots/6.png)
### 7
![7](screenshots/7.png)

## Technologies

- **Spring Boot**
- **Spring Framework**
- **Java**
- **MongoDB**
- **Thymeleaf**
- **Bootstrap**

## Features

- 📝 Article management system with CRUD operations
- 🔐 Admin-protected endpoints for content management
- 📄 Paginated article listing
- 📧 Contact form page
- 🛡️ CSRF protection for forms
- 📱 Responsive Bootstrap-based UI

## Installation & Setup

This is used as my personal website, https://sallai.tech, source-code not yet public

## API Endpoints


### Protected Admin Endpoints (Require ADMIN role)

| Method  | Endpoint          | Description                |
|---------|-------------------|----------------------------|
| POST    | /api/posts        | Create new blog post       |
| PUT     | /api/posts/{id}   | Update existing post       |
| DELETE  | /api/posts/{id}   | Delete post                |
| GET     | /createPosts      | Admin post creation form   |

### Public Endpoints

| Method  | Endpoint          | Description                |
|---------|-------------------|----------------------------|
| GET     | /                 | Home page with recent posts|
| GET     | /articles         | Paginated article list     |
| GET     | /articles/{id}    | Single article view        |
| GET     | /contactme        | Contact form page          |

## Code Structure

```
src/main/java/com/csabika98/blog/
├── BlogApplication.java # Main application entry point
├── config/ # Configuration classes
├── controllers/ # MVC Controllers
│ ├── ApiController.java # REST API endpoints
│ ├── ContactController.java # Contact form handling
│ ├── HomeController.java # Main page controllers
│ └── ...
├── models/ # Data models
├── repositories/ # MongoDB repositories
└── services/ # Business logic services
```


## Security Features

- Role-based access control for admin operations  
- CSRF protection for all forms  
- Secure session management  
- Input validation for blog posts and contact forms  

## Frontend Details

- Thymeleaf templates with Bootstrap 5  
- Responsive design  
- Dynamic content rendering  
- Form validation  
- Pagination support  

### Templates:

- `index.html`: Home page  
- `blog.html`: Article listing  
- `article.html`: Single post view  
- `contact.html`: Contact form  
- `createposts.html`: Admin post creation form  


