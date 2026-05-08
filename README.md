# 📊 Customer Portfolio Management System (FinVista)

## 📌 Overview
FinVista is an enterprise-grade, web-based Customer Portfolio Management System designed to streamline investment portfolio operations through secure, centralized, and role-based access.

The system addresses inefficiencies of manual portfolio handling by introducing automation, real-time insights, and robust security mechanisms for Customers, Advisors, and Admins.

---

## 🚨 Problem Statement
Traditional portfolio management systems are:

- Time-consuming and error-prone  
- Lacking real-time visibility  
- Missing role-based access control  
- Weak authentication and auditing  
- Difficult to scale  

---

## ✅ Solution Highlights
- 🔐 JWT-based secure authentication  
- 👤 Role-Based Access Control  
- 📈 Real-time analytics dashboards  
- ✅ OTP-based KYC workflow  
- 📜 Audit logging  
- 🧩 Scalable architecture (Factory Pattern)  

---

## 🏗️ Architecture and Technology Stack
- **Frontend:** Angular  
- **Backend:** ASP.NET Core Web API  
- **Database:** SQL Server  
- **Architecture:** Three-tier  

---

## 👥 User Roles

### 👤 Customer
- View portfolio  
- Track performance  
- Submit KYC  

### 📊 Advisor
- Manage customer portfolios  
- Analyze data  
- Generate reports  

### ⚙️ Admin
- Manage users  
- Approve KYC  
- Monitor logs  

---

## 🚀 Installation Guide

### ✅ Prerequisites
- .NET 8 SDK  
- Node.js (v18+)  
- SQL Server  

---

### 🔧 Backend Setup

    cd Customer_Portfolio
    dotnet restore
    dotnet ef database update
    dotnet run

---

### 🎨 Frontend Setup

    cd frontend
    npm install
    ng serve

---

## 🗄️ Database Configuration

Update `appsettings.json`:

    {
      "ConnectionStrings": {
        "DefaultConnection": "Server=YOUR_SERVER;Database=FinVistaDB;Trusted_Connection=True;TrustServerCertificate=True;"
      }
    }

---

## 🔄 Core Workflows

### 👤 Customer Flow
1. Login  
2. View dashboard  
3. Submit KYC  
4. Verify OTP  

### 📊 Advisor Flow
1. Login  
2. View customers  
3. Analyze portfolios  
4. Generate reports  

### ⚙️ Admin Flow
1. Login  
2. Review KYC  
3. Approve/Reject  
4. Manage users  

---

## 💡 Innovations
- Factory Pattern  
- Audit logging  
- OTP verification  
- Chart.js analytics  

---

## 🔮 Future Enhancements
- Mobile app  
- AI recommendations  
- Financial API integration  
- Notifications  

---

## 📌 Conclusion
FinVista delivers a secure, scalable, and efficient portfolio management platform with strong architecture and real-time insights.
