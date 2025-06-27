# 🎬 Database for an OTT platform

## 📌 Project Overview

This project involves the design and implementation of a comprehensive **relational database** system for an **OTT (Over-The-Top) platform**. The database is intended to serve the needs of multiple stakeholders including:

- General users/viewers
- Production houses
- Advertisers
- Platform administrators (owners)

The platform delivers a wide range of **web series** and manages **user subscriptions**, **advertisement campaigns**, **content metadata**, and **feedback mechanisms**. This database structure supports search and analytics functionalities for efficient content delivery, user personalization, and business intelligence.

---

## 🎯 Objective

The goal of this project is to:

- Design a robust and normalized relational database for an OTT platform.
- Implement the schema using **PostgreSQL**.
- Demonstrate the working system through a set of use-case driven **SQL queries**.

---

## 📚 Project Scope

With OTT platforms revolutionizing content delivery, this database serves as a backend for web or mobile applications. The database supports:

- User registration and login with preferences
- Genre/language-based content filtering
- Tracking of web series metadata: genre, cast, release date, ratings
- Feedback and rating system for both services and content
- Advertisement management (runtime, frequency, pricing)
- Subscription and rental service tracking

---

## 🧱 Key Features

### 👤 User Management
- Users register with personal details and content preferences.
- Users get a unique ID and login credentials.
- Mandatory and optional fields supported.

### 🎞️ Web Series Information
- Production houses provide detailed metadata for each web series.
- Includes genre, language, release date, certification, cast, and description.

### 💬 Feedback & Ratings
- Users rate and review content and services.
- Ratings help advertisers and production houses make informed decisions.

### 💳 Subscriptions & Rentals
- Users choose from multiple subscription packs and durations.
- Subscription changes are supported at any time.
- Rental options available for selected content.

### 📢 Advertisement Management
- Database stores data on ads: frequency, runtime, pricing, etc.
- Useful for advertisers and platform owners to plan campaigns.

---

## 🧩 Database Design Workflow

1. **Requirement Analysis**  
   Derived data requirements from platform functionality and user needs.

2. **Entity-Relationship Diagram (ERD)**  
   Identified major entities and relationships:
   - `User`, `WebSeries`, `Actor`, `ProductionHouse`, `Advertisement`, `Subscription`, `Rental`, `Feedback`, etc.

3. **Relational Schema Design**  
   Converted ERD to a normalized relational schema with primary & foreign keys.

4. **Normalization**  
   Ensured up to **BCNF (Boyce-Codd Normal Form)** to maintain data integrity and reduce redundancy.

5. **Implementation in PostgreSQL**  
   Created the schema using **DDL scripts** in PostgreSQL.

6. **Querying**  
   Ran sample SQL queries to:
   - Search for content by genre/language
   - View ratings and reviews
   - Analyze advertisement effectiveness
   - Track subscriptions and rentals

---

## 🛠️ Tech Stack

- **Database**: PostgreSQL  
- **Modeling Tools**: dia.io  
- **Development Tools**: pgAdmin  
- **Language**: pgSQL (DDL & DML)

---
