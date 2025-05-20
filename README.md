# 📌 DevMongoUI – MongoDB Admin Panel (Dockerized)

**DevMongoUI** is a lightweight, web-based MongoDB administrative interface built using **Mongo Express** and deployed via **Docker Compose**. It provides a simple and intuitive UI to visualize, manage, and interact with your MongoDB collections—perfect for developers and testers.

---

## ✅ Features

- **Connect to MongoDB** in seconds using Docker
- **View, create, update, and delete** databases and documents
- **Environment-based admin credentials** and secure connection setup
- Access through browser at **http://localhost:8081**
- Works seamlessly with local or Dockerized MongoDB instances

---

## ⚙️ Tech Stack

- **MongoDB** – NoSQL database
- **Mongo Express** – Web-based admin interface
- **Docker + Docker Compose** – Containerization and orchestration

---

## 🚀 Usage

1. Start the containers:
   ```bash
   docker compose -f mongodb.yaml up -d
