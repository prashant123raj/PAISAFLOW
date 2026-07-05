# Paisaflow 💸

Paisaflow is a full-stack financial application built with the MERN ecosystem. It includes a user-facing frontend client, an independent administration/client metrics dashboard, and a centralized backend API layer backed by MongoDB.

## 📁 Repository Structure

This project is organized as a monorepo containing three core sub-applications:

* *backend/* - Node.js & Express REST API handling database connectivity (MongoDB Atlas), custom schemas, operations, routes, and authentication.
* *frontend/* - React client application giving users access to features, entry pathways, and primary landing pages.
* *dashboard/* - An independent React layout tailored specifically for tracking comprehensive user summaries, charts, and metrics.

---

## 🚀 Live Deployments

The application is deployed live in production on *Render* across separate services:
* *Main Application UI:* [https://paisaflow-frontend.onrender.com](https://paisaflow-frontend.onrender.com)
* *Client Dashboard UI:* [https://paisaflow-dashboard.onrender.com](https://paisaflow-dashboard.onrender.com)
* *Backend Server API:* [https://paisaflow-backend.onrender.com](https://paisaflow-backend.onrender.com)

---

## 🛠️ Tech Stack

* *Frontend & Dashboard:* React, CSS3/Tailwind, Axios
* *Backend:* Node.js, Express.js, Mongoose, CORS, Body-Parser
* *Database:* MongoDB Atlas (Cloud)

---

## 💻 Local Installation & Setup

If you want to run this complete system on your machine locally, follow these installation steps:

### 1. Clone the repository
```bash
git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
cd PAISAFLOW
