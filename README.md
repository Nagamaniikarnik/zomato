# 🍽️ Zomato Clone – Docker & Tomcat Deployment

### 🚀 Project Overview
A fully responsive **Zomato-inspired food delivery web application**, built using **HTML, CSS, and JavaScript**, and deployed via **Apache Tomcat**, **Docker**, and **Docker Compose**.

This project demonstrates the end-to-end deployment of a static web app inside a **Tomcat container** using Docker — mimicking real-world DevOps workflows.
---
### 🧩 Tech Stack
- **Frontend:** HTML, CSS, JavaScript  
- **Server:** Apache Tomcat  
- **Containerization:** Docker, Docker Compose  
- **Version Control:** Git & GitHub  
---
### 🌟 Features
- 🏙️ Homepage with dynamic background & Zomato-style UI  
- 🍕 Restaurant sections (Pizza Express, Biryani House, Juice Junction, Sweet Tooth)  
- 📞 Contact form with interactive background  
- ⚙️ Dockerized deployment with Tomcat for scalable hosting  
- 💻 Responsive design for all devices  
---
### 🐳 Docker Setup

**1️⃣ Build Docker Image**
```bash
docker build -t zomato_image .
2️⃣ Run Container
docker run -d -p 8080:8080 --name zomato_container zomato_image
3️⃣ Check Logs (optional)
docker logs zomato_container
4️⃣ Stop and Remove Container
docker stop zomato_container
docker rm zomato_container

###📦 Docker Compose Deployment

If you’re using docker-compose.yml, run:
docker-compose up --build

Then access the web app at:
👉 http://localhost:8080
 or http://<your-EC2-public-IP>:8080

##📸 Preview

Home Page
<img width="1917" height="973" alt="Screenshot 2025-11-04 182400" src="https://github.com/user-attachments/assets/05c664a6-7764-4e27-98bd-8c9e5bc4d77a" />

