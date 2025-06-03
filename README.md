# 🚀 AI-Powered Mini CRM Platform

A lightweight, scalable CRM system built using **Spring Boot** and **MySQL**, designed to help businesses segment customers, create personalized campaigns, and leverage AI-driven insights for smarter marketing.

---

## 🧩 Features

- 📥 **Data Ingestion APIs** – Add customers and orders securely via REST APIs
- 🧠 **Dynamic Audience Segmentation** – Create custom rules (e.g., spend > ₹10K AND visits < 3)
- 📢 **Campaign Creation & Delivery** – Launch and log personalized campaigns
- 📊 **Campaign History Dashboard** – Track audience size, sent/failed status
- 🤖 **AI Integration** – Message suggestions, rule parsing, and performance summaries
- 🔐 **Authentication** – Google OAuth 2.0 login and access control
- 📤 **Simulated Vendor API** – Realistic message delivery (90% success, 10% fail)

---

## 🛠 Tech Stack

| Layer      | Tech               |
|------------|--------------------|
| Backend    | Java, Spring Boot  |
| Database   | MySQL              |
| Auth       | Google OAuth2      |
| AI Service | OpenAI API         |
| Docs       | Swagger / OpenAPI  |
| Optional   | React.js / Thymeleaf for UI |

---

## 📦 Setup Instructions

### 1. Clone the Repo
```bash
git clone https://github.com/your-username/mini-crm.git
cd mini-crm
