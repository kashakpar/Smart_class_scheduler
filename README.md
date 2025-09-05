# 🕒 Automated Timetable Scheduling System

## 📌 Project Overview
The **Automated Timetable Scheduling System** is a web-based platform designed to solve the challenges of manual timetable creation in higher education institutions.  
Using **Python (Flask + OR-Tools)** and **PHP/MySQL**, this system automatically generates **conflict-free timetables**, reallocates classes if clashes occur, and suggests alternative classrooms or slots.  

It ensures:
- No double booking of classrooms or faculties
- Efficient utilization of resources (classrooms, labs, faculties)
- Dynamic conflict detection and resolution
- Easy timetable management via a web interface

---

## 🚀 Features
- 🔑 **User Login** – Only authorized personnel can create/manage timetables  
- 📥 **Data Input** – Collects subject, faculty, classroom, and slot information via web forms  
- ⚡ **Smart Scheduling** – OR-Tools ensures clash-free timetables  
- 🔄 **Conflict Resolution** – Suggests free classrooms/slots if conflicts occur  
- 📊 **Optimized Timetable Generation** – Multiple options for admins to review and approve  
- 🗂 **Database Integration** – Timetables stored securely in MySQL/PostgreSQL  
- 🌐 **Web-based Platform** – Can be integrated with existing college portals  

---

## 🏗️ Tech Stack
- **Backend (Scheduling Engine):** Python (Flask)
- **Scheduling Algorithm:** Google OR-Tools (Constraint Programming CP-SAT Solver)
- **Frontend:** HTML, CSS, JavaScript (Fetch API)
- **Database:** MySQL / PostgreSQL
- **Server-side Integration:** PHP

---

## 📂 Project Structure
