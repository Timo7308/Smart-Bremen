# 🌍 Smart Bremen – The Forgotten City

**Smart Bremen** is a web platform developed to map and document informal urban practices in Bremen, Germany.

Informality includes activities, spaces, and initiatives that exist outside formal regulatory structures, such as graffiti, pop-up markets, temporary cultural spaces, and community-driven projects.

The project was developed at the **University of Bremen** by an interdisciplinary team of 15 students consisting of artistic, frontend, backend, and project management teams.

---

## 📌 Project Overview

The goal of Smart Bremen was to create a collaborative platform where users can discover and contribute informal activities throughout the city.

Registered users can submit new content, while administrators review and manage contributions before they are displayed on an interactive city map.

The platform combines a **React-based frontend** with a **Laravel REST API** and a **MySQL database**.

### Core Features

* User registration and authentication
* Role-based access control
* Creation and management of user-generated content
* Administrative verification of submitted content
* Interactive city map
* RESTful communication between frontend and backend
* User and account management

---

## 🎯 Project Objectives

* Create a user-friendly platform for documenting informal urban activities in Bremen
* Enable community participation through user-generated content
* Implement secure role-based access control
* Visualize informal practices on an interactive city map
* Build a modular and API-driven backend architecture
* Support future extensions of the platform

---

## 🧑‍💻 My Role – Backend Development

I was part of the **Backend Team**, which consisted of four developers.

My main responsibility was the implementation of **authentication, user management, and role-based access control** using Laravel.

### Authentication & User Management

I worked on:

* User registration
* User login and authentication
* User account management
* CRUD operations for user accounts
* Authentication-related API endpoints

### Role-Based Access Control

The platform distinguishes between several user roles:

* **Admin**
* **Artist**
* **Viewer**


### Team Collaboration

The project involved collaboration between several teams:

* Backend
* Frontend
* Artistic
* Project Management

We coordinated development through **weekly meetings**, GitHub, and Discord.

---

## 🛠️ Tech Stack

### Backend

* PHP
* Laravel 10
* MySQL
* REST APIs
* Laravel Middleware
* Authentication & Authorization

### Frontend

* React
* JavaScript
* HTML
* CSS

### Mapping

* Leaflet
* OpenStreetMap

### Development & Collaboration

* Git
* GitHub
* Discord

---

## 🏗️ Architecture

The application follows a client-server architecture:

```text
┌─────────────────────┐
│      Frontend       │
│       React         │
└──────────┬──────────┘
           │
           │ REST API
           ▼
┌─────────────────────┐
│       Backend       │
│     Laravel 10      │
│                     │
│ Authentication      │
│ Authorization       │
│ Business Logic      │
│ REST Endpoints      │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│       MySQL         │
│      Database       │
└─────────────────────┘
```

The frontend communicates with the Laravel backend through RESTful API endpoints. The backend handles authentication, authorization, application logic, and database access.

---

## 👥 Team Structure

The project was developed by a team of **15 students**.

| Team               | Members |
| ------------------ | ------: |
| Backend            |       4 |
| Frontend           |       2 |
| Artistic Team      |       7 |
| Project Management |       2 |

The interdisciplinary structure required coordination between technical development and the artistic and conceptual aspects of the project.

---

## 🖼️ Project Poster

The project poster provides an overview of the concept, implementation, and project results.

[View Smart Bremen Poster](./docs/smart-bremen-poster.png)

---

## 🔮 Future Improvements

Possible extensions of the platform include:

* Email verification during registration
* Improved mobile responsiveness
* Dedicated mobile application
* Social media sharing
* More granular user permissions
* Extended REST API functionality
* Enhanced user profiles
* User profile pictures and biographies
* Analytics for posts and user activity

---

## 🎓 Context

This project was developed as part of the **Digital Media program at the University of Bremen**.

It provided practical experience with:

* Backend development
* REST API design
* Authentication and authorization
* Relational databases
* Role-based access control
* Team-based software development
* API documentation
* Collaboration between frontend and backend teams

---

## 📜 License

This repository is provided for **documentation, educational, and portfolio purposes**.
