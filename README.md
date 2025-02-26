# 📖 Blog App

This project is a **microservices-based** application that allows users to create posts and comments, with a moderation system in place. It is designed with a scalable architecture and deployed using **Kubernetes**.

---

## 🛠 Technologies Used

This project leverages modern technologies:

### 📌 **Frontend**
- [React.js](https://reactjs.org/) - Library for building the user interface.
- [Axios](https://axios-http.com/) - HTTP client for API communication.

### 📌 **Backend (Microservices)**
- [Node.js](https://nodejs.org/) - JavaScript runtime for the backend.
- [Express.js](https://expressjs.com/) - Web framework for Node.js.
- [MongoDB](https://www.mongodb.com/) (optional) - NoSQL database for data persistence.
- [Mongoose](https://mongoosejs.com/) (if using MongoDB) - ODM for MongoDB in Node.js.

### 📌 **Service Communication**
- **Event Bus** - Event-driven communication between microservices.
- **REST API** - Each service exposes RESTful endpoints.

### 📌 **Orchestration & Deployment**
- [Docker](https://www.docker.com/) - Containerization of services.
- [Kubernetes](https://kubernetes.io/) - Container orchestrator.
- [Skaffold](https://skaffold.dev/) - Automates development and deployment on Kubernetes.

---
## 🚀 Getting Started

### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/odmoreno/blog-app.git
cd blog-app
```

## 2️⃣ **Start the Application with Skaffold**
```bash
skaffold dev
```
## 📌 **Project Structure**

```bash
blog-app/
│── client/         # Frontend application (React)
│── posts/          # Posts service
│── comments/       # Comments service
│── moderation/     # Moderation service
│── query/          # Query service for fetching combined data
│── event-bus/      # Handles event-driven communication
│── skaffold.yaml   # Skaffold deployment configuration
│── README.md       # This file
```
