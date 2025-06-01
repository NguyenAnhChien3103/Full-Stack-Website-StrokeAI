# 🧠 Smart Assistance System

**Smart Assistance System** is a smart healthcare monitoring platform designed to detect early signs and prevent strokes. The system consists of a mobile app (built with Flutter), a professional web dashboard (developed with Next.js), and a powerful backend (developed in ASP.NET Core C#) that processes health data, provides real-time alerts, and supports medical staff in decision-making.

---

## 🔎 Overview

- **Mobile App (Flutter)**: Allows users to track real-time vital signs such as blood pressure and heart rate, either manually or via connected devices.
- **Web Dashboard (Next.js)**: Empowers healthcare professionals to manage patient data, visualize health history, and respond to emergencies promptly.
- **Backend (ASP.NET Core C#)**: Handles business logic, data analysis, stroke risk prediction, and emergency alert delivery using **SignalR**.

---

## 🧠 Stroke Risk Prediction

The system predicts stroke risk based on a combination of three categories of medical indicators:

1. **Clinical Indicators**  
   Blood pressure, heart rate, BMI, medical history, symptoms, etc.

2. **Paraclinical Indicators**  
   Test results (e.g., blood test), diagnostic imaging (e.g., MRI, CT scan), etc.

3. **Molecular Biology Indicators**  
   Genetic markers, proteins, biochemical substances associated with stroke risk.

Prediction is performed using medical logic or AI/ML models (integrated or custom-built in C#).

---

## 🚨 Real-time Emergency Alerts (SignalR)

The system uses **SignalR** for real-time communication. When abnormal health metrics are detected:

- Emergency alerts are immediately pushed to doctors and caregivers through the dashboard or mobile app.
- SignalR ensures **instant, low-latency delivery** for critical medical events.
- Doctors can act quickly based on real-time data without waiting for manual reports.

---

## 🔧 Key Features

- 📲 **Real-time Health Monitoring**: Track vital signs continuously via the app.
- 🧠 **Stroke Risk Analysis**: Predict the probability of stroke using clinical, paraclinical, and molecular data.
- 🚨 **Emergency Alerts via SignalR**: Receive instant notifications for abnormal signs or emergencies.
- 👨‍⚕️ **Doctor Dashboard**: Manage patients, view records, and monitor alerts efficiently.
- 📈 **Health History Management**: Store, visualize, and analyze patient health trends over time.

---

## 🛠️ Technology Stack

| Layer             | Technology                |
|------------------|---------------------------|
| Frontend (Mobile) | Flutter                   |
| Frontend (Web)    | Next.js (React)           |
| Backend API       | ASP.NET Core (C#)         |
| Real-time Alerts  | SignalR                   |
| Database          | SQL Server                |
| Communication     | RESTful API, SignalR Hub  |
| Prediction Engine | C# Logic / ML Integration |

---

## 🎯 Project Goals

- Detect and prevent strokes **before they happen** through proactive monitoring.
- Assist medical professionals with **decision support tools**.
- Provide **real-time, actionable data** for better patient outcomes.
- Build a bridge between patients, healthcare systems, and families.

---

## 👥 Target Users

- High-risk individuals (e.g., elderly, hypertensive, diabetic).
- Doctors and healthcare workers in hospitals and clinics.
- Families monitoring loved ones remotely.

---
## Interface
![image](https://github.com/user-attachments/assets/50b046cc-0bd6-4948-820d-c1e2a71e676b)
![image](https://github.com/user-attachments/assets/ebd7191e-8d2c-4b09-92d1-4d139af432e2)
![image](https://github.com/user-attachments/assets/a533425d-3a11-4525-8847-521530de0c20)
![image](https://github.com/user-attachments/assets/db0163b7-479d-40ea-b32a-d08b5206ffc2)
![image](https://github.com/user-attachments/assets/53730cba-fba4-492c-9ac7-92464b113104)
![image](https://github.com/user-attachments/assets/fd710915-7194-4c2c-a060-e319b08b0856)
![image](https://github.com/user-attachments/assets/6552054a-2e2e-42c8-9ba1-111ad7fa77f0)
![image](https://github.com/user-attachments/assets/1ccb53e8-1fe4-4c10-a5ff-0c97984cc99b)
![image](https://github.com/user-attachments/assets/cf31cdea-16e6-433f-baa4-0595ad182d2a)







