# Blog Application with Admin Panel & Markdown Support  
**Powering [sallai.tech](https://sallai.tech)**  





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


![OldVersionPart1](https://github.com/user-attachments/assets/e60d5c9a-6578-4286-97db-987c4fcdda41)
![DropDownMenu](https://github.com/user-attachments/assets/0ad7579e-56be-437b-bafd-c88fe86700ec)
### 1
![MyProjects](https://github.com/user-attachments/assets/49790d72-9201-4a30-8b32-ae2d64cc4f8b)
![Admin Dashboard Preview](https://github.com/user-attachments/assets/7d2fa5b7-54bb-4fb7-b34a-2799611b66bb)

![HomePage](https://github.com/user-attachments/assets/bedc5ca4-0122-4b10-8d7f-58256cf90e09)
![LatestPost](https://github.com/user-attachments/assets/8d000329-4304-423d-bae6-f4cbf561d528)
![PostEditDelete](https://github.com/user-attachments/assets/b3147073-5dbe-4648-b4ad-8b1d2e2abec2)
![PostEdit1](https://github.com/user-attachments/assets/56d1d070-a489-4698-bf31-4dcfbf71a333)
![PostEdit2](https://github.com/user-attachments/assets/11419596-8d0d-49ef-82e6-c7fc3d1cfd76)
![PostDelete](https://github.com/user-attachments/assets/c29016f4-5bbd-4de2-8f00-4e8924556b9f)
![CreateNewPosts](screenshots/5.png)
### 8
![CreateNewPosts2](screenshots/6.png)

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

📬 Contact
For access requests or questions:

Email: sallcsa.csaba8@gmail.com

Website: sallai.tech
