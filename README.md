
# 🏫 IUO Staff Management System

![hero image](hero_staff.jpg)

### ⚠️ **Disclaimer**
> 🚫 **Source Code Not Publicly Available**  
> For data security and privacy reasons, the source code of this project is **not included in this repository**.  
>  
> If you're a **university administrator**, **potential client**, or **collaborator** interested in a **demo**, **customization**, or **deployment**, please contact me directly:

## 📞 Contact

📧 **Email**: [tariofiyoushell@gmail.com](mailto:tariofiyoushell@gmail.com)  
📱 **Phone**: +234 702 610 8529  
🌐 **Portfolio**: [https://legacy5234.github.io/My-Portfolio/](https://legacy5234.github.io/My-Portfolio/)  
🐙 **GitHub**: [Legacy5234](https://github.com/Legacy5234)

---

## 📘 Overview

The **IUO Staff Management System** was developed to replace the paper-based process of managing staff data at **Igbinedion University Okada**. The legacy process led to operational bottlenecks, limited visibility into staff activities, and difficulty updating or accessing staff data.

This digital platform provides a centralized interface for managing records, automating tasks, enforcing role-based access, and improving overall staff administration.

---

## ⚙️ System Workflow

### 1. 👥 Staff Record Management
- Admins can create, view, edit, and delete staff records.
- Bulk staff upload via CSV files is supported.
- Advanced search, filtering, and pagination included.

### 2. 🔐 Role Assignment & Access Control
- Staff roles can be assigned or modified by authorized personnel.
- Role-Based Access Control (RBAC) ensures appropriate data visibility and actions based on permission levels.

### 3. 🔁 Automated Background Tasks
- **Celery + Celery Beat** handle scheduled tasks like sending email reminders or maintenance alerts.
- Efficiently offloads time-based processes to background workers.

### 4. 📊 Dashboard & Activity Logs
- Each department or unit head has dedicated access to real-time staff statistics and records relevant to their specific department.
- System automatically logs activities like logins, edits, and assignments for transparency.

### 5. ✅ Authentication & Authorization
- Secure login with multiple permission levels (Admin, HR, Department Head).
- Password hashing and session handling follow best practices.

### 6. 🌐 Deployment
- App is hosted on Railway.app with PostgreSQL backend.
- Environment variables, media/static files, and database migrations are managed via CI/CD practices.

---

## 🌟 Key Benefits

- ✅ Centralized digital staff records
- ✅ Eliminates manual paperwork and redundancy
- ✅ Enforces permission-based access to sensitive data
- ✅ Reduces HR workload and streamlines onboarding
- ✅ Quick insights via visual staff metrics and role assignments
- ✅ Scalable for future features like payroll and attendance tracking

---

## 🔮 Upcoming Features (Planned)

- **Payroll Management Module**  
  Automated salary processing, deductions, bonuses, and exportable payslips.

- **Attendance Monitoring**  
  Track daily sign-ins/outs, leaves, and absenteeism.

- **Performance Evaluation Tools**  
  Structured appraisals, feedback logs, and promotion triggers.

- **Mobile Responsiveness**  
  Improved usability on tablets and smartphones for HR on-the-go.

- **Admin Analytics Dashboard**  
  Real-time metrics for hiring, departmental stats, and activity tracking.

---

