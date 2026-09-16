<div align="center">
  
# 🏡 Real Estate Due Diligence Platform

</div>

<div align="center">

**AI-powered Full Stack Platform for Property Verification, Risk Assessment & Due Diligence**

Built with **Spring Boot • React • PostgreSQL • JWT • Flyway • Tailwind CSS**

![Java](https://img.shields.io/badge/Java-17+-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38BDF8?style=for-the-badge&logo=tailwindcss&logoColor=white)

</div>

---

## 📖 Overview

The **Real Estate Due Diligence Platform** is a full-stack application designed to simplify property verification before real estate transactions.

Instead of manually checking legal documents, flood zones, zoning regulations, tax records, ownership history, and environmental risks, the platform consolidates everything into a single dashboard with AI-assisted risk summaries and detailed reports.

---

## ✨ Key Features

### 🔐 Authentication & Security

- JWT Authentication
- Google OAuth Login
- Role-Based Access Control
- Secure REST APIs
- Protected Admin Routes

### 👥 User Roles

- Buyer
- Property Owner
- Real Estate Agent
- Legal Reviewer
- Bank Representative
- Administrator

### 🏠 Property Management

- Register and manage properties
- Ownership tracking
- Property availability management
- Advanced search and filtering

### ⚠️ Risk Assessment

- Overall Risk Score
- Flood Risk Analysis
- Legal Risk Evaluation
- Environmental Risk Assessment
- Financial Risk Indicators
- Market Risk Insights
- Compliance Status Tracking

### 📄 Due Diligence Modules

- Flood Zone Records
- Property Tax History
- Zoning Verification
- Ownership Records
- AI Risk Summary
- Detailed Reports
- Missing Document Detection

### 💬 Communication

- Buyer-Owner Conversations
- Secure Messaging
- Activity Logging
- Admin Dashboard Analytics

---

## 🏗️ System Architecture

<AsyncImage query="Real Estate Due Diligence Platform architecture diagram Spring Boot React PostgreSQL JWT" aspectRatio="16:9" width="100%" maxHeight=420/>

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|-------------|
| Frontend | React, Vite, TypeScript, Tailwind CSS |
| Backend | Spring Boot, Spring Security, Spring Data JPA |
| Authentication | JWT, Google OAuth |
| Database | PostgreSQL |
| Migration | Flyway |
| Build Tool | Maven |
| API Testing | Postman |
| Version Control | Git & GitHub |

---

## 📂 Project Structure

```text
Real-Estate-Due-Diligence-Platform/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── src/main/java/
│   ├── src/main/resources/
│   ├── src/test/
│   └── pom.xml
│
└── README.md
```

---

## 🗄️ Database Modules

The platform includes dedicated modules for:

- Users
- Properties
- Ownership Records
- Flood Zone Records
- Risk Summary
- Property Tax
- Zoning
- Reports
- Conversations
- Messages
- Dashboard Statistics
- Activity Logs
- Role Requests

---

## 🚀 Getting Started

### Prerequisites

- Java 17+
- Node.js 18+
- PostgreSQL
- Maven (Wrapper Included)

---

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/kartikgarg146/Real-Estate-Due-Diligence-Platform.git
cd Real-Estate-Due-Diligence-Platform
```

---

### 2️⃣ Backend Setup

Navigate to the backend folder:

```bash
cd backend
```

Run the backend:

```bash
./mvnw spring-boot:run
```

Backend runs at:

```text
http://localhost:8081
```

---

### 3️⃣ Frontend Setup

Open another terminal:

```bash
cd frontend
npm install
npm run dev
```

Frontend runs at:

```text
http://localhost:5173
```

---

## ⚙️ Environment Variables

Create the required environment variables before running the project.

### Backend

| Variable | Description |
|----------|-------------|
| `DB_URL` | PostgreSQL connection URL |
| `DB_USERNAME` | Database username |
| `DB_PASSWORD` | Database password |
| `JWT_SECRET` | JWT signing secret |
| `MAIL_USERNAME` | SMTP username |
| `MAIL_PASSWORD` | SMTP password |
| `GOOGLE_CLIENT_ID` | Google OAuth Client ID |
| `GOOGLE_CLIENT_SECRET` | Google OAuth Secret |

---

## 📡 API Overview

### Authentication

| Method | Endpoint |
|--------|----------|
| POST | `/api/auth/register` |
| POST | `/api/auth/login` |
| POST | `/api/auth/google` |

### Property

| Method | Endpoint |
|--------|----------|
| GET | `/api/properties` |
| POST | `/api/properties` |
| GET | `/api/properties/{id}` |

### Risk Assessment

| Method | Endpoint |
|--------|----------|
| GET | `/api/risk-summary/{propertyId}` |
| GET | `/api/flood-zone/{propertyId}` |
| GET | `/api/zoning/{propertyId}` |
| GET | `/api/property-tax/{propertyId}` |

### Admin

| Method | Endpoint |
|--------|----------|
| GET | `/api/admin/dashboard` |
| GET | `/api/admin/dashboard/overview` |
| GET | `/api/admin/dashboard/activity` |

---

## 📊 Platform Workflow

<AsyncImage query="Real Estate Due Diligence Platform workflow diagram property registration risk assessment reports" aspectRatio="16:9" width="100%" maxHeight=420/>

---

## 🎯 Core Capabilities

- Secure JWT Authentication
- Google OAuth Integration
- Role-Based Authorization
- AI-Assisted Risk Assessment
- Property Verification
- Flood Zone Analysis
- Legal Due Diligence
- PostgreSQL + Flyway Migrations
- RESTful API Architecture
- Responsive Modern UI

---

## 📈 Future Enhancements

- GIS-based Property Visualization
- AI Document Verification
- PDF Report Export
- Email Notifications
- Real-time Chat Improvements
- Property Valuation Prediction
- Advanced Analytics Dashboard
- Mobile Application Support

---

## 👥 Contributing

This project was developed collaboratively as part of the **Infosys Springboard Internship** by **Team-01**.

| Contributor | Primary Contribution |
|-------------|----------------------|
| **Kartik Garg** | Frontend development, API integration, and backend integration |
| **Bhavya Rai** | Frontend development and UI implementation |
| **Imran S** | Backend development and API implementation |
| **Bhavinaya Shri** | Backend development and business logic implementation |
| **Samridhi Prakash** | Database design, schema management, and data integration |
| **Mithun A** | Database design, migrations, and data management |

**Mentored by:** **springboardmentor198 (Infosys Springboard)**

### 🤝 Development Workflow

- Collaborative development using Git and GitHub.
- Feature branches merged into the `develop` branch.
- Database versioning managed with Flyway.
- Spring Boot powered the backend services, while React + Vite delivered the frontend experience.

---

## 📄 License

This project is licensed under the **MIT License**.

---

<div align="center">

### ⭐ If you found this project interesting, consider giving it a star!

</div>
