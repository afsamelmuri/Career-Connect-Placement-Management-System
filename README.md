
# Career Connect: Placement Management System

A full-stack web application designed to streamline the campus recruitment process by bridging the gap between students, placement cells, and recruiters.

## 🚀 Overview

The Career Connect Platform is a centralized solution developed as part of an M.Tech industrial internship project. It automates placement workflows, manages company visits, filters student eligibility, and enables data-driven placement tracking.

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript, React.js, Tailwind CSS  
- **Backend:** Python, FastAPI  
- **Database:** MySQL  
- **Middleware:** FastAPI (RESTful APIs)  
- **API Testing:** Postman, Swagger  
- **Version Control:** Git, GitHub  
- **Tools Used:** VS Code, MySQL Workbench, React Dev Tools  

## 📌 Key Features

- 🔐 **Role-based Login & Signup** for Students and Admins with secure authentication  
- 🗂️ **Company Visit Info Module:** Add/manage company profiles, visit dates, and eligibility criteria  
- 📋 **Dashboard:** View real-time statistics of student placements, drives, and registrations  
- 🎓 **Eligibility & Placement Management:** Filter students dynamically based on CGPA, stream, backlogs, etc.  
- 📁 **Resume Management:** Students can upload/update resumes linked to their profiles  
- 📊 **Analytics:** Placement stats, eligible/placed student counts, downloadable reports  

## 🧱 Database Tables

- `institutes`: Institution details  
- `company_profiles`: Company details  
- `company_visits`: Visit tracking (date, time, location)  
- `placement_records`: Student placement outcomes  
- `students`: Academic and contact details  
- `users`: Login credentials, roles  
- `skills_certifications`, `education_details`, `internships_projects`, `awards_achievements`: Supporting eligibility filtering  

## ⚙️ Installation (Local Setup)

```bash
# 1. Clone the repository
git clone https://github.com/your-username/career-connect.git
cd career-connect

# 2. Backend Setup
cd backend
python -m venv env
source env/bin/activate  # Windows: env\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload

# 3. Frontend Setup
cd frontend
npm install
npm start

# Ensure MySQL server is running and credentials match your backend config.


career-connect/
│
├── backend/
│ ├── main.py
│ ├── models/
│ ├── routers/
│ ├── db/
│ ├── requirements.txt
│ └── README.md
│
├── frontend/
│ ├── public/
│ ├── src/
│ └── package.json
│
├── assets/
│ ├── img/
│ └── screens/
│ ├── login.png
│ ├── dashboard.png
│ ├── company-visit.png
│
├── .gitignore
├── README.md
└── LICENSE
