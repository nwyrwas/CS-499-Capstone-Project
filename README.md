# 🧠 CS-499 Capstone Project: Animal Shelter Data Analytics Dashboard  
**Author:** Nicholas Wyrwas  
**Program:** B.S. Computer Science – Software Engineering  
**Institution:** Southern New Hampshire University  
**Completion Date:** November 2025  

---

## 📘 Project Overview
This capstone project represents the culmination of my Computer Science degree, integrating knowledge across software engineering, secure coding, data management, and visualization.  

The **Animal Shelter Data Analytics Dashboard** is a full-stack data visualization platform built using **Python Dash**, **MongoDB**, and **Matplotlib**. It enables users to view, search, and interact with real-time data about animal rescue and adoption patterns in a secure, visually engaging format.

This project evolved from my original **CS-340 Client-Server Development** artifact — a Flask-based CRUD system — into a **modern interactive dashboard** that demonstrates scalability, usability, and security.

---

## 🎯 Objectives
- Transform a static CRUD web app into a responsive, data-driven visualization dashboard.  
- Apply secure coding principles to all database interactions.  
- Integrate analytical insights through charts, filters, and real-time updates.  
- Implement modular architecture to support maintainability and scalability.  
- Showcase mastery of SNHU’s computer science program outcomes.

---

## 🧩 Original Artifact – CS-340 Client-Server Development
**Repository:** [CS-340-12210-M01-Client-Server-Development](https://github.com/nwyrwas/CS-340-12210-M01-Client-Server-Development)

The original system was a **Flask + MongoDB** application that allowed authenticated users to perform CRUD operations for animal records.  
While functional, it lacked:
- Real-time data visualization  
- Modular architecture for reuse  
- Strong input validation and secure query handling  
- User-focused interface design  

---

## 🚀 Enhanced Artifact – Capstone Dashboard
The enhanced version re-engineers the original system into a modern analytics platform featuring:  
- **Dash Framework Integration** for interactive, component-based web UI  
- **Matplotlib Visualization** for dynamic adoption trend graphs  
- **MongoDB Optimization** with parameterized queries and indexing  
- **Data Security Controls** aligned with SEI CERT and OWASP standards  
- **Dark-mode UI** for accessibility and consistent professional design  

---

## 🛠️ Technical Stack
| Layer | Technology |
|-------|-------------|
| Front-End | Dash (HTML/CSS/JS via Python Components) |
| Back-End | Python Flask + Dash Callback Functions |
| Database | MongoDB (CRUD + Aggregation Pipelines) |
| Visualization | Matplotlib, Plotly, Dash Graphs |
| Environment | Virtualenv (Python 3.13), GitHub, VS Code, macOS |
| Deployment | GitHub Pages (Documentation) + Local Execution for App |


---

## 💡 Key Features
- **Search and Filtering:** Query records by animal type, breed, outcome, or location.  
- **Interactive Charts:** Real-time data visualization for adoption rates and intake trends.  
- **Map Integration:** Visualizes animal rescue data geographically (via Leaflet).  
- **Dark Theme UI:** Clean, accessible interface suitable for presentation and professional use.  
- **Secure Database Interaction:** Validated inputs and parameterized queries prevent injection.  
- **Scalable Design:** Modular code structure for easy extension or integration with APIs.  

---

## 🧠 Skills Demonstrated
- Software design and development  
- Data structures and algorithms  
- Databases and data analytics  
- Secure coding and input validation  
- System integration and version control  
- UI/UX design and human-computer interaction  

---

## 🎓 Alignment with Program Outcomes
| Program Outcome | Implementation Example |
|-----------------|------------------------|
| **Software Design and Development** | Modular Python architecture using Dash components. |
| **Algorithms and Data Structures** | CRUD + query optimization through MongoDB pipelines. |
| **Databases** | Secure CRUD operations with parameterization and indexing. |
| **Security** | Implemented defense-in-depth and CERT standards. |
| **Collaboration and Communication** | GitHub version control, code documentation, and code review video. |

---

## 📺 Demonstration
A narrated walkthrough of the dashboard explains the system architecture, user interface, and enhancement process.  
*(Coming soon — YouTube link will be embedded in portfolio site.)*

---

## 🧪 Setup and Execution

### 1. Clone Repository
```bash
git clone https://github.com/nwyrwas/CS-499-Capstone-Project.git
cd CS-499-Capstone-Project/Final_Project

**python3 -m venv dashenv
source dashenv/bin/activate   # On macOS/Linux
dashenv\Scripts\activate      # On Windows
**

pip install -r requirements.txt

python app.py

```

## 🖼️ Preview
Below is a snapshot of the final dashboard interface showcasing live analytics, search functionality, and data visualization.

![Dashboard Preview](screenshot.jpg)





