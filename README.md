# 🛡️ ScamShield – Community Driven Fraud Detection Platform  

<p align="center">
  <a href="https://scamshield-xjip.vercel.app/">
    <img src="https://img.shields.io/badge/Live%20Frontend-Visit-blue?style=for-the-badge" />
  </a>
  <a href="https://scamshield-2.onrender.com">
    <img src="https://img.shields.io/badge/Backend-API-green?style=for-the-badge" />
  </a>
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge" />
</p>

---

## 📌 Overview  

Online scams are growing rapidly — phishing links, fake job offers, UPI fraud, and spam calls are everywhere.  

**ScamShield** is a community-driven platform that allows users to **verify suspicious phone numbers, URLs, and payment IDs instantly**.  

It acts as a **centralized fraud detection system powered by real user reports**, helping people make safer decisions online.

---

## ❗ Problem  

- 📈 Rapid increase in online fraud cases  
- ❌ No quick way to verify suspicious contacts  
- 🧠 Lack of awareness  
- 💸 Financial and data loss  

---

## 💡 Solution  

ScamShield provides:  

- 🔍 Instant scam verification  
- 📝 Community-based reporting  
- 📊 Shared scam database  

👉 Creating a **collaborative fraud prevention ecosystem**

---

## ⚙️ Features  

### 🔍 Scam Verification  
Search phone numbers, URLs, or UPI IDs to check reports.  

### 📝 Community Reporting  
Users can submit scam details with descriptions.  

### 📊 Centralized Database  
MongoDB stores all scam reports.  

### ⚡ Debounced Search  
Optimized search reduces unnecessary API calls.  

### 📄 Pagination  
Handles large datasets efficiently.  

### 🗂 Filtering & Sorting  
Filter by:
- OTP Scam  
- UPI Fraud  
- Phishing  
- Fake Job Offers  

Sort by:
- Latest  
- Most reported  

### 🔐 Authentication  
- Sign Up  
- Login  
- Secure reporting  

### 🎨 Responsive UI  
Works on mobile, tablet, and desktop.  

### 🌙 Dark / Light Mode  
Better user experience with themes.  

---

## 🛠 Tech Stack  

### Frontend  
- React.js  
- Tailwind CSS  
- React Router  

### Backend  
- Node.js  
- Express.js  

### Database  
- MongoDB  

---

## 🌐 Live Links  

- 🔗 Frontend: https://scamshield-xjip.vercel.app/  
- 🔗 Backend: https://scamshield-2.onrender.com  

---

## 📊 Database Structure  

Each scam report contains:  

- 📞 Phone Number / URL / UPI ID  
- 🏷 Scam Type  
- 📝 Description  
- 📈 Report Count  
- 👤 Reported By  

---

## 🚀 How It Works  

1. User searches suspicious data  
2. Backend checks MongoDB  
3. If found → shows scam reports  
4. If not → user can report  
5. Data becomes available for others  

---

## 💻 Run Locally  

### 1️⃣ Clone Repository  

```bash
git clone https://github.com/your-username/scamshield.git
cd scamshield