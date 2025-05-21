# 🔗 Spring Boot URL Shortener

A robust and secure URL Shortener service built with Spring Boot, Spring Security, and PostgreSQL. It enables users to convert long URLs into short, shareable links with support for analytics, user roles, and custom expiration.

---

## 🚀 Features

- 🔐 User Authentication (Guest, Registered, Admin)
- ✂️ Shorten long URLs into unique, short links
- 📅 Expiry support for short links (30-day default for guests, customizable for users)
- 🔄 URL Redirection with error handling for invalid/expired links
- 📊 Click Analytics: Track the number of visits per shortened URL
- 🧑‍💼 Admin Dashboard to manage all URLs
- 🗃️ Public/Private URL support

---

## 🛠️ Tech Stack

- **Backend:** Spring Boot, Spring Security, Spring Data JPA
- **Database:** PostgreSQL, FlywayDB (Migrations)
- **Frontend:** Thymeleaf, Bootstrap CSS
- **Containerization:** Docker
- **Language:** Java 21

---

## ✅ Prerequisites

- Java 21+
- Docker (for containerized DB or deployment)
- Maven
- PostgreSQL (or use Docker image)

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/springboot-url-shortener.git
cd springboot-url-shortener
