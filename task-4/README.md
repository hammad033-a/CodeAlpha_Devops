# 🚀 Task 4: Dockerized Professional DevOps Dashboard

## Project Overview
This project demonstrates the containerization of a high-performance web application using **Nginx** and **Docker**. Instead of a simple static page, I have developed and deployed a professional **DevOps Internship Dashboard** that mimics real-world enterprise portals.

## 🛠 Tech Stack
- **Web Server:** Nginx (Alpine-based for minimal footprint)
- **Frontend:** HTML5, CSS3 (Glassmorphism UI), Bootstrap 5, FontAwesome
- **Containerization:** Docker Desktop for MacOS
- **Architecture:** Port Mapping (80:80) & Layered Image Optimization

## 📂 Project Structure
- `Dockerfile`: Contains build instructions for the Nginx image.
- `html/index.html`: The professional multi-section dashboard code.
- `screenshots/`: Visual proof of the running environment.

## ⚡ Deployment Commands
To reproduce this environment, run the following:

1. **Build the Image:**
   docker build -t codealpha-official:v1 .

2. **Run the Container:**
   docker run -d -p 80:80 --name hammad-web-server codealpha-official:v1

## 📊 Results
- **Responsive Design:** Optimized for Desktop, Tablet, and Mobile.
- **Service Status:** Container is running 24/7 with zero downtime.
- **Port Mapping:** Host traffic on port 80 is successfully routed to the container.

---
**Developed by Hammad Sattar** | *DevOps Intern at CodeAlpha*
