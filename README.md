# student-serverless-3-tier-app
# 🚀 Serverless 3-Tier Student Management App (AWS)

## 📌 Project Overview
This project is a serverless 3-tier web application built using AWS services.  
It allows users to add student data via a web interface, which is processed and stored in a cloud database.

---

## 🏗️ Architecture

User → CloudFront → S3 → API Gateway → Lambda → DynamoDB

---

## 🛠️ Tech Stack

- Frontend: HTML,
- Backend: AWS Lambda (Python)  
- API: Amazon API Gateway (REST)  
- Database: Amazon DynamoDB  
- Hosting: Amazon S3 (Private)  
- CDN: Amazon CloudFront (with OAC)

---

## 🔐 Security Features

- S3 bucket is private (no public access)  
- Access controlled via CloudFront OAC  
- API secured with proper CORS configuration  

---

## ⚙️ Features

- Add student data (ID, Name, Age)  
- Serverless backend (no servers required)  
- Scalable and highly available  
- Secure architecture using AWS best practices  

---

## 📂 Project Structure

frontend/ → Static website  
lambda/ → Backend code  
docs/ → Architecture diagram  

---

## 🚀 Live Demo

👉 https://YOUR-CLOUDFRONT-URL

---

## 🧠 What I Learned

- Building serverless architectures  
- Securing S3 using CloudFront OAC  
- Integrating API Gateway with Lambda  
- Working with DynamoDB  
- Debugging real-world AWS issues  

---

## 📸 Architecture Diagram

(Add your diagram here)

---
