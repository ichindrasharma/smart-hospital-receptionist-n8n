# 🏥 Smart Hospital Receptionist (n8n)

## 📌 Overview
This project is an automated hospital receptionist system built using n8n.  
It handles patient queries and assigns doctors based on availability.

---

## 🚀 Features
- QR / Link based patient form
- Categorizes cases: General, Emergency, Mental Health
- Automatically assigns available doctor
- Sends email with doctor name and ward details
- Reduces manual workload

---

## ⚙️ Tech Stack
- n8n (Workflow Automation)
- Email Integration
- Form Handling

---

## 🧠 Workflow
1. User scans QR or opens link  
2. Fills form with query  
3. n8n processes input  
4. Checks doctor availability  
5. Sends email with details  

---

## 📷 Screenshots
<img src = "ScreenShot/1_filling form by patient.png">
<img src = "ScreenShot/2_form_submited .png">
<img src = "ScreenShot/5_n8n workflow against query.png">
<img src = "ScreenShot/3_Mail to Doctor.png">
<img src = "ScreenShot/4_Mail to Patient.jpeg">

---

## 📂 How to Use
1. Import `n8n-workflow.json` into n8n  
2. Configure email credentials  
3. Run workflow  

---

## 💡 Future Improvements
- Database integration
- Real-time doctor availability dashboard
- AI-based triage system
