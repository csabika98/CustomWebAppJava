# Blog Application with Admin Panel & Markdown Support  
**Powering [sallai.tech](https://sallai.tech)**  

![Admin Dashboard Preview](https://github.com/user-attachments/assets/7d2fa5b7-54bb-4fb7-b34a-2799611b66bb)  
*Active development shown by real commits:*  
![Commit History](https://github.com/user-attachments/assets/e0d8a643-e677-41e9-aecf-385d3606bb00)  
![Recent Updates](https://github.com/user-attachments/assets/a50c62f3-8ec4-4cce-bfb4-abda525cdaed)  

## ✨ Key Features  

### 🖥️ Admin Panel  
- Full CRUD operations for blog management  
- Role-based access control (Admin/User roles)  
- Dashboard with activity metrics  

### 📝 Content Management  
- **Markdown support** - Write posts in `.md` files and upload directly  
- Drag-and-drop media uploads  
- Scheduled publishing  

### 👥 User System  
- Secure registration & authentication  
- Profile management  
- Commenting system  

### 🚀 Technical Highlights  
- Java Spring Boot backend  
- MongoDB database  
- Thymeleaf + Bootstrap frontend  
- Responsive mobile-ready UI  

---

## 📸 Application Screenshots  

![image](https://github.com/user-attachments/assets/7d2fa5b7-54bb-4fb7-b34a-2799611b66bb)
![image](https://github.com/user-attachments/assets/e60d5c9a-6578-4286-97db-987c4fcdda41)
![image](https://github.com/user-attachments/assets/0ad7579e-56be-437b-bafd-c88fe86700ec)

### 1
![image](https://github.com/user-attachments/assets/49790d72-9201-4a30-8b32-ae2d64cc4f8b)
### 2
![image](https://github.com/user-attachments/assets/abf2a28b-7018-457e-9a85-0041f342c7ea)
### 3
![1](screenshots/1.png)
### 4
![2](screenshots/2.png)
### 5
![3](screenshots/3.png)
### 6
![4](screenshots/4.png)
### 7
![5](screenshots/5.png)
### 8
![6](screenshots/6.png)
### 9
![7](screenshots/7.png)
---

## 🛠️ Technical Stack  

**Backend**  
- Java 17  
- Spring Boot 3.x  
- Spring Security  
- Spring Data MongoDB  

**Frontend**  
- Thymeleaf templates  
- Bootstrap 5  
- Vanilla JS + jQuery  

**Database**  
- MongoDB Atlas  

**Infrastructure**  
- Docker containerization  
- CI/CD pipeline  

---

## 🔐 Security Features  

- Role-based authorization  
- CSRF protection  
- Password encryption (BCrypt)  
- Secure session management  
- Input sanitization for XSS prevention  

---

## 📂 Project Structure  
```
com.csabika98.blog/

├── config/
├── controllers/
│ ├── AdminController.java
│ ├── ApiController.java
│ └── ...
├── models/ 
├── repositories/ 
├── services/
├── util/ 
└── resources/
├── templates/ 
├── static/
└── application.properties
```


---

## 🔌 API Endpoints  

### Public Routes  
| Method | Path          | Description          |
|--------|---------------|----------------------|
| GET    | /             | Homepage with posts  |
| GET    | /posts/{slug} | Single post view     |
| POST   | /contact      | Submit contact form  |

### Admin Routes  
| Method | Path            | Description            |
|--------|-----------------|------------------------|
| POST   | /admin/posts    | Create new post        |
| PUT    | /admin/posts/{id} | Update post           |
| GET    | /admin/dashboard | Management console    |

### Authentication  
| Method | Path       | Description          |
|--------|------------|----------------------|
| POST   | /register  | User registration    |
| POST   | /login     | User login           |
| POST   | /logout    | Session termination  |

---

## 🚀 Getting Started  

*Note: Source currently private while in active production use*  

1. **Prerequisites**:  
   - Java 17 JDK  
   - MongoDB 6.0+  
   - Maven 3.8+  

2. **Configuration**:  
Create application.properties with:  
``` 
spring.data.mongodb.uri=mongodb://localhost:27017/blogdb
spring.security.user.name=admin
spring.security.user.password=securepassword
```


3. **Running**:  
```bash
mvn spring-boot:run
```

📬 Contact
For access requests or questions:

Email: sallcsa.csaba8@gmail.com

Website: sallai.tech
