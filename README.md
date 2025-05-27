# 🚀 Discovery Swift

**Discovery Swift** is a full-stack mobile application designed to improve customer convenience and reduce administrative burdens in the healthcare space. Built using **Flutter** (UI), **Python** (backend), and optional **Node.js** services, the app focuses on digitizing and streamlining patient onboarding at medical practices.

---

## 💡 Project Idea

### Smart Form Autofill and QR-Based Document Sharing for Medical Visits

Discovery Swift introduces an innovative feature that simplifies the first-time visit process for patients:

- Patients often need to fill out repetitive medical forms on their first visit to a healthcare provider.
- With Discovery Swift, users can **photograph the form** using the app.
- The app applies **OCR and AI** to understand the form fields and **autofill** them using the patient's existing Discovery medical profile (e.g., personal details, allergies, history).
- A **PDF of the completed form** is generated and paired with a **unique QR code**.
- The patient presents the QR code at reception; the staff scans it to instantly access the digital form — enabling **secure, paperless data exchange**.

This feature supports Discovery’s broader digital healthcare goals and enhances the overall patient experience by eliminating redundant manual tasks.

---

## 📁 Project Structure

discovery_swift/  
├── frontend/ # Flutter mobile app  
├── backend_python/ # Python backend for processing forms, OCR, etc.  
├── backend_node/ # Optional: real-time services, microservices  
├── shared/ # Common models, constants, data schemas  
├── docs/ # Architecture and planning docs

---

## 🧰 Tech Stack

- **Frontend:** Flutter
- **Backend:** Python (e.g., FastAPI or Flask)
- **Optional Services:** Node.js for microservices or real-time logic
- **OCR + AI:** For recognizing and interpreting form fields
- **QR Code Generation:** For easy, secure document transfer
- **Authentication:** Firebase Auth or JWT
- **Database:** Firestore, PostgreSQL, or MongoDB (flexible)

---

## ⚙️ Getting Started

```bash
# Flutter Frontend
cd frontend/
flutter pub get
flutter run

# Python Backend
cd backend_python/
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python app/main.py

# Node.js Backend (Optional)
cd backend_node/
npm install
npm run dev

```
---
## 🔒 License & Ownership

This project is developed for and owned by Discovery Limited. All intellectual property rights, including the code, design, and associated materials, are the property of Discovery and are not to be used, copied, or distributed without express permission.

© Discovery Limited. All rights reserved.