Blood Bank Management System – Enhanced with Secure OTP Authentication

Overview
This Blood Bank Management System is developed to facilitate connections between blood donors and recipients, streamlining the blood donation process.  
Originally derived from an open-source initiative, this iteration has been upgraded with Secure OTP Authentication to enhance both security and dependability.

Features
- Registration for Donors & Recipients
- Search Functionality for Available Blood Groups
- Request and Approval Mechanism for Blood Donations
- Secure OTP-Based Login and Signup
  - Users receive a One-Time Password (OTP) via email during the signup or login process.
  - The OTP is set to expire after a predetermined duration for increased security.
- Integration with MySQL Database
- Responsive User Interface for both desktop and mobile devices

Tech Stack
- Frontend: HTML, CSS, JavaScript, Bootstrap
- Backend: PHP
- Database: MySQL
- Additional Services: SMTP/PHPMailer for OTP email transmission

How OTP Authentication Functions
1. Signup/Login → The user inputs their email and password.
2. OTP Request → The system generates a 6-digit OTP and dispatches it to the registered email address.
3. Verification → The user is required to enter the OTP within a specified time frame.
4. Access Granted → Only entries of valid and timely OTPs will permit access.
 Installation Guide
