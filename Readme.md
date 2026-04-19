# 🚀 Node.js EC2 Docker CI/CD App

A simple Node.js (Express) application deployed on an AWS EC2 instance using Docker, with automated CI/CD using GitHub Actions.

---

## 🌐 Live Application

👉 http://16.171.19.173:3000

---

## 🐳 Docker Image

👉 https://hub.docker.com/r/arnav3101ap/aws-app

---

## 📂 GitHub Repository

👉 https://github.com/arnavprajapati/nodejs-ec2-docker-app

---

## ⚙️ Tech Stack

* Node.js (Express)
* Docker
* AWS EC2 (Ubuntu)
* GitHub Actions (CI/CD)

---

## 📦 Features

* Lightweight Express server
* Fully Dockerized application
* Deployed on AWS EC2
* CI/CD pipeline for automatic Docker build & push
* Publicly accessible via EC2 Public IP

---

## 🚀 Getting Started

### Run Locally

```bash
git clone https://github.com/arnavprajapati/nodejs-ec2-docker-app.git
cd nodejs-ec2-docker-app
npm install
node index.js
```

👉 Open: http://localhost:3000

---

## 🐳 Docker Usage

### Pull Docker Image

```bash
docker pull arnav3101ap/aws-app
```

### Run Container

```bash
docker run -d -p 3000:3000 --name app arnav3101ap/aws-app
```

👉 Open: http://localhost:3000

---

## 🔁 CI/CD Pipeline

GitHub Actions is configured to:

* Trigger on push to `main` branch
* Build Docker image
* Push image to Docker Hub

Workflow file:

```
.github/workflows/deploy.yml
```

---

## ☁️ AWS Deployment

* EC2 Instance (Ubuntu)
* Docker installed on instance
* Application runs inside container
* Port **3000** exposed
* Security Group allows inbound traffic on port 3000

---

## 📁 Project Structure

```
.
├── Dockerfile
├── index.js
├── package.json
├── package-lock.json
├── .gitignore
└── .github/workflows/deploy.yml
```

---

## 🧪 API Endpoints

| Endpoint  | Description           |
| --------- | --------------------- |
| `/`       | Returns Hello from EC2 🚀 |
| `/health` | Health check endpoint |

---

## 🧠 Learnings

* Docker containerization
* EC2 deployment & networking
* Port exposure & security groups
* CI/CD automation using GitHub Actions

---

## 👨‍💻 Author

**Arnav Prajapati**

---

## ⭐ Result

Successfully deployed a Dockerized Node.js application on AWS EC2 with a working CI/CD pipeline using GitHub Actions.
