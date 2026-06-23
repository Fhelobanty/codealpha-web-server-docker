# 🚀 CodeAlpha Task 4 - Web Server Using Docker

![Docker](https://img.shields.io/badge/Docker-Containerization-blue?logo=docker)
![Nginx](https://img.shields.io/badge/Nginx-Web%20Server-green?logo=nginx)
![HTML5](https://img.shields.io/badge/HTML5-Frontend-orange?logo=html5)
![GitHub](https://img.shields.io/badge/GitHub-Version%20Control-black?logo=github)

## 📌 Project Overview

This project was completed as part of the **CodeAlpha Internship Program (Task 4: Web Server Using Docker)**.

The objective of this project was to understand Docker fundamentals, deploy a web server using Docker, build a custom Docker image, manage containers, and monitor container performance.

A custom web page was created using HTML and served using the **Nginx Web Server** running inside a Docker container.

---

## 🎯 Objectives

* Understand Docker fundamentals.
* Create and manage Docker containers.
* Deploy a web server using Docker.
* Build a custom Docker image using a Dockerfile.
* Monitor and troubleshoot containers.
* Apply Docker best practices.

---

## 🛠 Technologies Used

* Docker
* Nginx
* HTML5
* CSS3
* Git
* GitHub
* Visual Studio Code
* PowerShell
* Windows 10 Pro

---

## 📂 Project Structure

```text
codealpha-web-server-docker
│
├── index.html
├── Dockerfile
├── README.md
├── .gitignore
└── screenshots
```

---

## 🐳 Dockerfile

```dockerfile
FROM nginx:latest

COPY index.html /usr/share/nginx/html/index.html

EXPOSE 80
```

---

## ⚙️ Docker Commands Used

### Pull Nginx Image

```bash
docker pull nginx
```

### View Images

```bash
docker images
```

### Create a Container

```bash
docker run -d -p 8080:80 --name mywebserver nginx
```

### Build Custom Image

```bash
docker build -t codealpha-webserver .
```

### Run Custom Container

```bash
docker run -d --name codealpha-container -p 8080:80 codealpha-webserver
```

### View Running Containers

```bash
docker ps
```

### View Logs

```bash
docker logs codealpha-container
```

### Inspect Container

```bash
docker inspect codealpha-container
```

### Monitor Resource Usage

```bash
docker stats
```

---

## 🚀 How to Run the Project

### Clone Repository

```bash
git clone https://github.com/Fhelobanty/codealpha-web-server-docker.git
```

### Navigate to Project Directory

```bash
cd codealpha-web-server-docker
```

### Build Docker Image

```bash
docker build -t codealpha-webserver .
```

### Run Container

```bash
docker run -d -p 8080:80 --name codealpha-container codealpha-webserver
```

### Access Application

Open your browser and visit:

```text
http://localhost:8080
```

---

## 📊 Features Implemented

✅ Docker Containerization

✅ Nginx Web Server Deployment

✅ Custom Docker Image

✅ Dockerfile Configuration

✅ Port Mapping

✅ Container Lifecycle Management

✅ Container Monitoring

✅ Troubleshooting and Inspection

✅ GitHub Version Control

---

## 📸 Screenshots
<img width="1900" height="868" alt="Codealphadocker" src="https://github.com/user-attachments/assets/26ef3408-200c-4baa-acd1-7ff40ce0a9ad" />
<img width="1897" height="926" alt="Codealphadocker2" src="https://github.com/user-attachments/assets/a325e552-8bf1-4866-8399-828e864e2bc5" />



```text
screenshots
```

Recommended screenshots:

* Website Interface
* Docker Build Process
* docker ps Output
* docker images Output
* docker logs Output
* docker stats Output

---

## 📈 Results

The project was successfully completed and demonstrated practical experience in:

* Docker containerization
* Web server deployment
* Container management
* Monitoring and troubleshooting
* Docker best practices

---

## 🎓 Internship

**CodeAlpha Internship Program**

**Task 4: Web Server Using Docker**

---

## 👨‍💻 Author

### Atoyebi Micheal Ademola

DevOps Engineer | Cloud Enthusiast

GitHub: https://github.com/Fhelobanty

---

## ⭐ If you found this project useful, consider giving it a star.
