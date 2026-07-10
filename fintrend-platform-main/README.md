# 📊 FinTech Analytics Dashboard

A comprehensive **FinTech Analytics Dashboard** built using **React.js**, **Vite**, and **Chart.js** to help Asset Management Companies (AMCs) analyze investor behavior, Assets Under Management (AUM), SIP trends, compliance alerts, churn prediction, and transaction analytics.

The application provides executive-level insights through interactive dashboards and data visualizations, enabling fund managers to make informed investment and operational decisions.

---

## 🚀 Features

### 📌 Executive Dashboard

* Overall business performance summary
* Total Assets Under Management (AUM)
* Net Inflows & Outflows
* Active Investors
* Key Performance Indicators (KPIs)

### 📈 AUM Analytics Dashboard

* Daily, Monthly, and Yearly AUM Growth
* Fund-wise Asset Distribution
* Portfolio Performance
* Category-wise Analysis

### 💰 SIP Trend Analysis

* Monthly SIP Registrations
* SIP Renewal Rate
* SIP Cancellation Analysis
* Investor Retention Trends

### 🔥 Transaction Heatmap

* Daily Transaction Activity
* Monthly Investment Trends
* Peak Transaction Analysis
* Heatmap Visualization

### ⚠️ AML & Compliance Dashboard

* AML Alert Monitoring
* Suspicious Transaction Detection
* Compliance Status
* Risk Level Indicators

### 🤖 Churn Prediction Dashboard

* High Risk Investors
* Churn Probability
* Investor Segmentation
* Retention Insights

### 📄 Report Generator

* Dashboard Reports
* Export-ready Analytics
* Executive Summary

---

## 🛠️ Tech Stack

| Technology        | Purpose              |
| ----------------- | -------------------- |
| React.js          | Frontend Framework   |
| Vite              | Build Tool           |
| JavaScript (ES6+) | Programming Language |
| Chart.js          | Data Visualization   |
| React Router      | Navigation           |
| CSS3              | Styling              |

---

## 📂 Project Structure & Directory Guide

```text
Final SIP Trend Analysis Dashboard/
├── backend/                        # Backend API Server & Services (Express.js)
│   ├── src/
│   │   ├── config/                 # System configuration store files (e.g., settingsStore.js)
│   │   ├── controllers/            # Controller layers handling incoming HTTP requests & response structures
│   │   ├── repositories/           # Repositories executing SQL queries & mapping data columns (e.g., user.repository.js)
│   │   ├── routes/                 # Endpoint path definitions mapping API requests to controllers
│   │   ├── services/               # Core business rules engines (e.g., analytics.service.js, investment.service.js)
│   │   └── utils/                  # Helper utilities including WORM audit logger and unique ID generators
│   ├── db/                         # Local SQLite database fallbacks for offline testing
│   └── server.js                   # Application entry point booting both Express HTTP and WebSocket live transaction servers
│
├── frontend/                       # Interactive Frontend Web App (React + Vite + Chart.js)
│   ├── src/
│   │   ├── components/             # Reusable UI dashboard tabs (Executive, AUM, SIP, Heatmap, Churn, Compliance)
│   │   ├── constants/              # Global fund scheme keys, navigation parameters, and Chart.js themes
│   │   ├── context/                # PlatformContext state provider managing API syncing and WebSocket connections
│   │   ├── services/               # Network client layer dispatching fetch calls to the Express gateway
│   │   ├── App.jsx                 # App layout configuration, router routes, and sidebar navigation
│   │   ├── main.jsx                # React app entry mounting node
│   │   └── index.css               # Core CSS design system containing custom themes and glassmorphism styling variables
│   └── vite.config.js              # Vite bundler configurations routing `/api` requests to Express on port 5000
│
├── supabase/                       # Remote Supabase Cloud Database integration
│   └── schema.sql                  # PostgreSQL table creation structures, relation constraints, and check limits
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/lalathegreat/SIP-Trend-Analysis.git
```

Navigate into the project

```bash
cd SIP-Trend-Analysis
```

Install dependencies

```bash
npm install
```

Run the development server

```bash
npm run dev
```

Open your browser

```
http://localhost:5173
```

---

## 🎯 Future Enhancements

* AI-powered Investment Recommendations
* Real-time Market Data Integration
* User Authentication
* PDF Report Export
* Cloud Deployment
* Machine Learning Models

---

## 👨‍💻 Developer

**Lalatendu Bal**

Final Year Engineering Student

Interested in FinTech, Data Analytics, AI, and Full Stack Development.

---
## 📸 Dashboard Preview

### Executive Dashboard

![Executive Dashboard](Screenshots/executive-dashboard.png)

### AUM Dashboard

![AUM Dashboard](Screenshots/aum-dashboard.png)

### SIP Trend Dashboard

![SIP Dashboard](Screenshots/SIP-dashboard.png)

### AML Dashboard

![AML Dashboard](Screenshots/AML-dashboard.png)

### Churn Prediction Dashboard

![Churn Dashboard](Screenshots/churn-dashboard.png)

### Transaction Heatmap

![Transaction Heatmap](Screenshots/transaction-heatmap.png)
## ⭐ If you like this project

Please consider giving this repository a ⭐ on GitHub.
