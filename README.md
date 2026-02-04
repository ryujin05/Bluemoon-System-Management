# 🏢 BlueMoon System Management

> 🏠 Professional apartment management system with **Backend API** and **Frontend (Electron)**. Comprehensive solution for managing household registrations, resident profiles, fee collections, statistics, and report generation.

[![GitHub](https://img.shields.io/badge/GitHub-ryujin05-blue?logo=github)](https://github.com/ryujin05)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Node.js](https://img.shields.io/badge/Node.js-16+-green?logo=node.js)](https://nodejs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript)](https://www.typescriptlang.org/)

---

## ✨ Key Features

- 📋 **Household Management** - Manage household registrations and resident profiles
- 👥 **Resident Tracking** - Complete resident and dweller information system
- 💰 **Fee Collection** - Track payments and payment history
- 📊 **Statistics & Reports** - Advanced analytics and report generation
- 🔐 **Authentication** - User authentication and authorization

---

## 🏗️ Architecture

| Component | Technology |
|-----------|-----------|
| **Backend** | TypeScript, Node.js, Prisma |
| **Frontend** | Electron, HTML/CSS/JavaScript |
| **Database** | PostgreSQL (via Prisma) |

---

## 📁 Directory Structure

```
.
├── backend/              # 🔧 API server + Prisma ORM
│   ├── src/
│   ├── prisma/
│   └── package.json
├── frontend/             # 🎨 Electron app + UI
│   ├── src/
│   └── package.json
├── docker-compose.yml    # 🐳 Docker configuration
├── run.ps1               # ⚡ PowerShell quick start
└── RUN.bat               # ⚡ CMD quick start
```

---

## 🚀 Quick Start

### Prerequisites
- Node.js 16+
- npm or yarn
- PostgreSQL (for local development)

### Environment Setup

Create `.env` file in the `backend/` directory:

```bash
# backend/.env
DATABASE_URL="postgresql://USER:PASSWORD@HOST:PORT/DATABASE?schema=public"
JWT_SECRET="your-secret-key-here"
```

### Installation & Running

#### 📦 Backend

```bash
cd backend
npm install
npm run dev
```

#### 🎨 Frontend

```bash
cd frontend
npm install
npm run start
```

### ⚡ Using Scripts

**PowerShell:**
```powershell
./run.ps1
```

**CMD:**
```cmd
RUN.bat
```

---

## 🐳 Docker

Deploy the entire stack with Docker:

```bash
docker-compose up --build
```

---

## 🎥 Live Demo

**Watch the full demo:** [Google Drive Link](https://drive.google.com/file/d/119FUXDSIRNWbuGZ6H-aLnEaBOx5E3p1Y/view?usp=sharing)

---

## 📋 GitHub Deployment

### Important Notes
- ⚠️ **Never commit `.env` files** - They contain sensitive credentials
- ✅ `.gitignore` is configured to exclude sensitive files automatically

### Push to GitHub

```bash
git init
git add .
git commit -m "Initial commit: BlueMoon System Management"
git remote add origin https://github.com/your-username/your-repo-name.git
git branch -M main
git push -u origin main
```

---

## 🛠️ Tech Stack

<div align="center">

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Electron](https://img.shields.io/badge/-Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/-Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</div>

---

## 📄 Project Structure

```
Backend Routes:
├── /auth          - 🔐 Authentication
├── /hokhau        - 📋 Household Management
├── /nhankhau      - 👥 Resident Management
├── /khoanthu      - 💰 Fee Collection
├── /thongke       - 📊 Statistics
└── /export        - 📥 Report Export
```

---

## 👨‍💻 Author

<div align="center">

**Pham The Dat**

[![GitHub](https://img.shields.io/badge/GitHub-ryujin05-black?logo=github&logoColor=white&style=flat-square)](https://github.com/ryujin05)
[![Email](https://img.shields.io/badge/Email-dphamthe67%40gmail.com-red?logo=gmail&logoColor=white&style=flat-square)](mailto:dphamthe67@gmail.com)

</div>

---

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

<div align="center">

**Made with ❤️ by Pham The Dat**

⭐ If you found this project useful, please consider giving it a star on GitHub!

</div>
