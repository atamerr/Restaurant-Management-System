# 🍽️ Restaurant Management System
> A clean, modular Java implementation for managing restaurant operations, developed with a strong focus on Object-Oriented Design.

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

---

## 📖 Overview
This repository contains a **Restaurant Management System** designed to handle complex workflows including user authentication, meal management, and table reservations. The project focuses on translating UML architectural designs into functional, clean Java code.

## 🚀 Key Features
* **Multi-Role Access:** Dedicated modules for Admins, Users, and Guests.
* **Meal & Menu Control:** Full management of restaurant offerings.
* **Reservation Engine:** Efficient logic for table booking and guest tracking.
* **Modular Design:** High-quality class hierarchy for easy maintenance.

---

## 👥 Engineering Team (Collaborators)
Each member focused on a specific domain of the system to ensure specialized development and modularity:

| Collaborator | Technical Contribution | Modules |
| :--- | :--- | :--- |
| **Ahmed Tamer** | **Architecture Lead** | `Main`, `Reservation`, `Admin (Meals)`, `Meals` |
| **Zayd Ali** | **User Management** | `Admin (User)`, `Admin (Meals)` |
| **Abdulrahman Elbaiti** | **Logistics Manager** | `Table`, `Guest`, `Admin (Table)` |
| **Omar Ahmed** | **Operations Service** | `User`, `Meals`, `Reception` |

---

## 🛠️ Core OOP Implementation
The system strictly adheres to **Object-Oriented Programming** principles to ensure code reusability and scalability:

* **Encapsulation:** All entity data (Users, Meals, Tables) are protected using private fields and accessed via secure Getters/Setters.
* **Abstraction:** Complex internal logic is hidden behind simplified interfaces for handling reservations and administrative tasks.
* **Inheritance & Polymorphism:** Utilized for managing different user roles (Admin, Guest, User) with shared base attributes and specialized behaviors.



