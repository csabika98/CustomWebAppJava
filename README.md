# 📝 Blog Application with Admin Panel & Markdown Support  
**Powers [sallai.tech](https://sallai.tech)**  

---
* Real commits on a private repo, as this actively used for https://sallai.tech

🚧 _This project is in active development — real progress with real commits:_  
![Commit History](https://github.com/user-attachments/assets/e0d8a643-e677-41e9-aecf-385d3606bb00)  
![Recent Updates](https://github.com/user-attachments/assets/a50c62f3-8ec4-4cce-bfb4-abda525cdaed)

---

## ✨ Features  

### 🖥️ Admin Panel  
- Create, edit, and delete blog posts  
- Admin/User role support  
- Dashboard with site activity  

### 📝 Easy Content Management  
- **Markdown support** – write blog posts as `.md` files  
- Upload media with drag & drop  
- Schedule posts for future publishing  

### 👥 User Accounts  
- Sign up, log in, and manage profiles securely  
- Users can comment on posts  

### ⚙️ Technology Used  
- **Backend:** Java (Spring Boot)  
- **Database:** MongoDB  
- **Frontend:** Thymeleaf + Bootstrap  
- **Fully responsive** (mobile friendly)  

---

## 📸 Screenshots with Explanations  

### 🧪 Old Version Preview  
![Old Version Part 1](https://github.com/user-attachments/assets/e60d5c9a-6578-4286-97db-987c4fcdda41)

---

### 📂 Navigation Menu  
![Dropdown Menu](https://github.com/user-attachments/assets/0ad7579e-56be-437b-bafd-c88fe86700ec)

---

### 📑 Project List Page  
![My Projects](https://github.com/user-attachments/assets/49790d72-9201-4a30-8b32-ae2d64cc4f8b)

---

### 🧭 Admin Dashboard  
![Admin Dashboard](https://github.com/user-attachments/assets/7d2fa5b7-54bb-4fb7-b34a-2799611b66bb)

---

### 🏠 Homepage (Public View)  
![Homepage](https://github.com/user-attachments/assets/bedc5ca4-0122-4b10-8d7f-58256cf90e09)

---

### 🆕 Latest Post Display  
![Latest Post](https://github.com/user-attachments/assets/8d000329-4304-423d-bae6-f4cbf561d528)

---

### ✏️ Post Management (Edit/Delete)  
![Post Edit/Delete](https://github.com/user-attachments/assets/b3147073-5dbe-4648-b4ad-8b1d2e2abec2)

---

### 📝 Editing a Post (View 1)  
![Post Edit 1](https://github.com/user-attachments/assets/56d1d070-a489-4698-bf31-4dcfbf71a333)

---

### 📝 Editing a Post (View 2)  
![Post Edit 2](https://github.com/user-attachments/assets/11419596-8d0d-49ef-82e6-c7fc3d1cfd76)

---

### ❌ Delete Post Confirmation  
![Post Delete](https://github.com/user-attachments/assets/c29016f4-5bbd-4de2-8f00-4e8924556b9f)

---

### 🆕 Create New Post (Part 1)  
![Create New Post](screenshots/5.png)

---

### 🆕 Create New Post (Part 2)  
![Create New Post 2](screenshots/6.png)

---

## 🛠️ Tech Stack  

**Backend**  
- Java 17  
- Spring Boot 3.x  
- Spring Security  
- MongoDB (via Spring Data)  

**Frontend**  
- Thymeleaf  
- Bootstrap 5  
- Vanilla JavaScript + jQuery  

**DevOps & Infra**  
- Docker  
- CI/CD  

---

## 🔐 Security Features  

- Admin/User role permissions  
- CSRF protection  
- Password hashing with BCrypt  
- Secure sessions  
- Input sanitization (XSS protection)  

---

## 🗂️ Project Structure  

```
com.csabika98.blog/
├── config/
├── controllers/
│   ├── AdminController.java
│   ├── ApiController.java
│   └── ...
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

## 📡 API Overview  

### 🌐 Public Endpoints  
| Method | Path            | Description         |
|--------|-----------------|---------------------|
| GET    | `/`             | Homepage            |
| GET    | `/posts/{slug}` | View single post    |
| POST   | `/contact`      | Contact form        |

### 🔐 Admin Endpoints  
| Method | Path                 | Description         |
|--------|----------------------|---------------------|
| POST   | `/admin/posts`       | Create post         |
| PUT    | `/admin/posts/{id}`  | Edit post           |
| GET    | `/admin/dashboard`   | Admin dashboard     |

### 👤 Authentication  
| Method | Path        | Description         |
|--------|-------------|---------------------|
| POST   | `/register` | Register new user   |
| POST   | `/login`    | Log in              |
| POST   | `/logout`   | Log out             |

---

## 📬 Contact  

Questions or access requests?  
📧 Email: [sallcsa.csaba8@gmail.com](mailto:sallcsa.csaba8@gmail.com)  
🌐 Website: [sallai.tech](https://sallai.tech)
