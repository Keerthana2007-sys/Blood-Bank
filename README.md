# Blood Bank Management System – Enhanced with Secure OTP Authentication

## 📌 Overview
This is a **Blood Bank Management System** designed to connect blood donors and recipients, making blood donation processes easier and faster.  
Originally based on an open-source project, this version has been **enhanced with Secure OTP Authentication** to improve security and reliability.

## 🚀 Features
- 🩸 **Donor & Recipient Registration**
- 🔍 **Search for Available Blood Groups**
- 📅 **Request and Approve Blood Donations**
- 🔐 **Secure OTP-Based Login and Signup**
  - Users receive a One-Time Password (OTP) via email during signup or login.
  - OTP expires after a set time for added security.
- 🗄 **MySQL Database Integration**
- 📱 **Responsive UI** for both desktop and mobile

## 🛠 Tech Stack
- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Backend:** PHP
- **Database:** MySQL
- **Additional Services:** SMTP/PHPMailer for OTP email delivery

## 🔑 How OTP Authentication Works
1. **Signup/Login** → User enters their email and password.
2. **OTP Request** → System generates a 6-digit OTP and sends it to the registered email.
3. **Verification** → User must enter the OTP within a limited time window.
4. **Access Granted** → Only valid and timely OTP entries allow access.

## 📂 Installation Guide
1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/BloodBank-OTP.git
