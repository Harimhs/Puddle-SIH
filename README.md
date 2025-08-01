#  PUDDLE LMS – AI-Powered Learning Platform

> Real-time LMS with student/faculty portals, course uploads, dashboards, and integrated AI query support.

---

##  Overview

PUDDLE is a full-stack Learning Management System designed to modernize academic engagement. It offers role-based access, real-time course interaction, and an embedded AI chatbot to support student queries using natural language.

---

##  Features

- 🎓 **Student & Staff Login** with secure authentication (JWT)
- 📁 **Course Uploads & Material Sharing** via staff dashboard
- 📊 **Progress Tracking** with visual dashboards
- 💬 **AI Assistant** using OpenAI API for 24/7 academic support
- 🔐 **Role-based access control** for content visibility
- 🌐 **RESTful API architecture** for backend integration

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Django REST](https://img.shields.io/badge/Django%20REST-092E20?style=flat&logo=django&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-38B2AC?style=flat&logo=tailwind-css&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)

---

##  Running Locally

```bash
# Clone the repo
git clone https://github.com/Harimhs/Puddle-SIH.git
cd Puddle-SIH

# Set up virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run server
python manage.py runserver
