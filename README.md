# Smart Timetable Scheduling System 📅

A complete **Full-Stack Application** designed to automate the process of academic timetable generation and resource management. This application provides an intuitive web interface for administrators to manage everything related to faculty scheduling.

## 🚀 Features

### **Data Management**
- **🏢 Program & Division Management:** Configure Undergraduate (UG) or Postgraduate (PG) programs, semesters, and individual divisions.
- **👨‍🏫 Faculty Management:** Add teachers, set their shift timings (e.g., 09:00 - 17:00), track leaves, and assign subjects.
- **📚 Subject Management:** Add theoretical and practical/lab subjects and set the required weekly lecture count.
- **🏫 Room Management:** Manage classroom and laboratory spaces with designated capacities.

### **Automated Timetable Generation**
The system uses constraint-based scheduling algorithms to perform automatic generation without conflict:
- Ensures **no double-booking** for teachers or classrooms.
- Respects **custom faculty shift timings**.
- **Leave Management:** Automatically replaces teachers on leave with available teachers during their shift.
- Distributes lectures cleanly, avoiding back-to-back duplicate slots for faculty.

### **Views & Dashboards**
The user-friendly frontend provides comprehensive viewing dashboards:
- **Class / Room Timetable:** See which classes are happening in which rooms throughout the week.
- **Faculty Timetable:** Dedicated schedules showing exactly where and when an individual teacher is assigned.
- **Division Timetable:** The default student view showing a division's entire weekly schedule.

### **Export Support**
- 📄 Direct integration to **Export Timetables to PDF** format for printing and sharing using ReportLab.

## 🛠️ Technology Stack
- **Frontend:** HTML5, CSS3, Vanilla Javascript.
- **Backend:** Python (Flask).
- **Database:** SQLite3.
- **PDF Generation:** ReportLab.

## 📂 Project Structure
Currently, the `frontend/` layer holds all essential UI views:
- Dashboard, Timetable Tables, Data Management Forms (`add_teacher_html.txt`, `manage_data_html.txt`, etc.).

---
*Built to streamline college & school administrations with zero conflict and total flexibility.*
