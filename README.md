<h1 align="center">🏠 Bachelor Room Management App</h1>
<p align="center">
A collaborative web application built with <strong>Django</strong> to help roommates manage shared services and track expenses within their living space.
</p>

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-blueviolet?style=for-the-badge&logo=bootstrap&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![Status](https://img.shields.io/badge/Project-Active-brightgreen?style=for-the-badge)

</div>

---

## 📄 **Description**

The **Bachelor Room Management App** provides a centralized platform for roommates to manage common tasks, expenses, and room activities.

A user can create a **Room**, which generates a **unique invite code** that can be shared with other roommates. Once joined, all members can access a **shared dashboard** to:

- Add services like *Groceries*, *Wi-Fi Bill*, *Electricity*, etc.
- Log costs associated with each service
- Track shared expenses with transparency

Additionally:
- The **Room Owner** gets a private **Owner Dashboard** showing monthly expense summaries.
- **Admins (staff users)** get a full **Admin Panel** to monitor all rooms and services.

---

## ⭐ **Key Features**

### 🔐 User Authentication
- Secure registration
- Email verification
- Login & logout

### 🏠 Room Management
- Create a new room for your living group  
- Automatically generates a unique invite code  
- Members can join using the invite code  
- Each room has its own shared space

### 🧑‍🤝‍🧑 Shared Dashboard
- Shows all services added by room members  
- Members can add new services  
- Every update is visible to all room members

### 💸 Expense Tracking
- Add detailed cost records per service  
- Include description + amount (in ₹)  
- Track monthly expenses  
- Total expenses shown in owner dashboard

### 🎛️ Role-Based Access
- **Room Owner** gets:
  - Owner Dashboard  
  - Monthly summary  
  - Member count  
  - Total services count  

- **Admin** (staff users) get:
  - Centralized admin panel  
  - Edit/delete any service  
  - Global statistics  

### 🖥 Admin Panel (Staff Users)
- View all services across all rooms  
- Search & filter service records  
- Full CRUD access  
- See global system statistics  

---

## 🧰 **Technology Stack**

| Layer | Technology |
|------|------------|
| **Backend** | Django, Python |
| **Frontend** | HTML, CSS, Bootstrap 5 |
| **Database** | SQLite 3 |
| **Other** | Django Auth, Django ORM |

---

## 📸 **Screenshots**

> Add your screenshots in a folder named `screenshots/` and reference them here:

