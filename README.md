# 🌾 AgriSolution  
### Modernizing Agriculture Through Secure Web Technology

AgriSolution is a full-stack, PHP-based web application designed to digitally connect **farmers, suppliers, and consumers** through a secure and efficient agricultural ecosystem.  
Developed as an academic project at **COMSATS University Islamabad**, the system demonstrates strong **backend engineering, secure authentication, and database-driven architecture**.

---

## ✨ Project Overview

- 🌱 Digitizes agricultural product discovery and transactions  
- 🔐 Designed with **security-by-design** principles  
- 🛒 Functional e-commerce workflow  
- 🧑‍🌾 Farmer-centric usability with protected data handling  

---

## 🚀 Key Features

- **Dynamic Product Catalog**  
  Browse agricultural products, tools, and resources with structured listings.

- **Secure Authentication System**  
  Role-based **Sign In / Sign Up** using PHP sessions.

- **Shopping Cart Functionality**  
  Fully implemented `add_to_cart.php` enabling seamless transactions.

- **Centralized Resource Hub**  
  Informational pages for project details and agricultural guidance.

---

## 🛠️ Technology Stack

| Layer | Technologies |
|------|-------------|
| **Frontend** | HTML5, CSS3 (Responsive UI) |
| **Backend** | PHP |
| **Database** | MySQL |
| **Configuration** | `config.php` |
| **Additional Logic** | Hack |
| **Server** | XAMPP / WAMP |

---

## 🛡️ Security Implementation

Security was treated as a **core architectural requirement**:

- **SQL Injection Prevention**  
  User inputs are sanitized and handled securely via `config.php`.

- **Session Security**  
  Protected routes using PHP session management.

- **Credential Safety**  
  Centralized database configuration with controlled access.

- **Separation of Concerns**  
  Clean separation between UI, business logic, and database layers.

---

## 🏗️ Project Structure

```text
Agriculture-solution-Web/
│
├── HomePage.php         # Main entry point with featured resources
├── product_list.php    # Dynamic agricultural product catalog
├── add_to_cart.php     # Cart logic and session-based state handling
├── SignIn.php          # Secure user authentication interface
├── config.php          # Database connection & security configuration
└── AboutUs.html        # Project mission and background
```
---

## ⚙️ Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/MohsinHaiderSultan/Agriculture-solution-Web.git
```

### 2️⃣ Setup Server Environment

1. Install XAMPP or WAMP
2. Move the project folder to:

```bash
htdocs/
```

### 3️⃣ Configure Database

1. Open phpMyAdmin

2. Create a new database

3. Import the provided SQL schema

Update database credentials in:

```bash
config.php
```

### 4️⃣ Launch Application

Open your browser and navigate to:

```bash
http://localhost/Agriculture-solution-Web
```

## 🔐 Security Practices Implemented

- ✅ Session-based authentication  
- ✅ Input validation & sanitization  
- ✅ Secure database connection handling  
- ✅ Prepared structure for CSRF protection  
- ✅ Password handling ready for hashing upgrades  

---

## 🎯 Learning Outcomes

- Full-stack **PHP web development**  
- Secure authentication & session management  
- **MySQL** database integration  
- Cybersecurity best practices in web applications  
- Clean project structuring & deployment workflow  

---

## 🔮 Future Enhancements

- 🧑‍🌾 Role-based dashboards (Farmer / Admin / Buyer)  
- 💳 Payment gateway integration  
- 🔌 REST API support  
- 🛡️ Advanced security features (CSRF tokens, improved hashing)  
- 📱 Mobile-first responsive redesign  


---

## 👨‍💻 Author

<p align="center">   <b>Mohsin Haider Sultan, Rana Mudassir Ali, Syed M. Shoaib Amjad</b><br>   🎓 High-Achieving Computer Science Graduates <br>   🧠 Artificial Intelligence • 🛡️ Cybersecurity • 🌐 Full-Stack Development<br>   🏫 COMSATS University Islamabad </p> <p align="center">   <a href="https://github.com/MohsinHaiderSultan">     <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />   </a>   <a href="https://www.linkedin.com/in/mohsin-haider-sultan-498b5b251">     <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />   </a>   <a href="mailto:mohsinhaidersultan001@gmail.com">     <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />   </a>   <a href="https://mohsinhaidersultan.github.io/Portfolio/">     <img src="https://img.shields.io/badge/Portfolio-36BCF7?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio" />   </a> </p> <p align="center">   <i>"Transforming complex logic into secure, scalable, and intelligent digital realities."</i> </p>

