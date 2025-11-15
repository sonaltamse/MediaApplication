# Spring Boot Social Demo App

A demo Spring Boot application that implements a simple social networking model with essential JPA relationships and REST APIs.

---

## 🚀 Features

### 🧑 Users & Profiles
- Each user has a **one-to-one** profile (bio, location, etc.)
- Demonstrates JPA’s `@OneToOne` mapping

### 👥 Groups
- Users can join multiple groups  
- Groups can have multiple users  
- Implements **many-to-many** with a join table

### 📝 Posts
- A user can create posts  
- Posts can belong to groups  
- Demonstrates entity links and simple CRUD handling

---
