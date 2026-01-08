# **CompList – Work Checklist & Performance Tracking Platform**

**CompList** is a desktop application built on **C# .NET WinForms**, designed to help organizations manage work checklists, monitor task execution, and track employee performance. By combining **QR-based workflows** with **Google Forms and Sheets integration**, the system enables employees to submit task updates quickly, while managers can review progress and KPIs in a centralized platform.

For detailed explanations, workflows, and screenshots, please refer to the **Report.pdf** - full project information.

---

## 🔍 System Overview

CompList offers a complete workflow for checklist management: from creation and task assignment to data collection, reporting, and performance evaluation. It is suitable for enterprises, departments, and project teams requiring structured reporting and efficient task tracking.

---

## ⚙ Key Features

### Checklist Management

* Create, edit, and organize checklists by project, department, or schedule
* Assign responsibilities to employees or teams
* Customize checklist titles, descriptions, and task items

### QR-Based Task Execution

* Automatically generate QR codes for each checklist
* Deploy QR codes at work locations for easy access
* Archive QR codes for recurring or one-time tasks

### Data Collection & Synchronization

* Employees submit task completion via Google Forms
* Data stored in Google Sheets and synchronized automatically
* Checklist statuses updated based on collected data

### User Roles & Access Control

* **System Administrator:** Full access to configuration, data, and reports
* **Department Supervisor:** Manage checklists, assign tasks, and review progress
* **Employee:** Execute tasks and submit updates
* **External Personnel:** Limited access per assignment

### Reporting & KPI Tracking

* Export reports in **PDF** or **Excel**
* Include department, timestamp, and pagination
* Filter by department, status, or period
* Track KPIs such as completion rate and overdue tasks
* Email reminders for pending items

---

## 🧪 Technology Stack

* **Programming Language:** C#
* **Framework:** .NET WinForms
* **Data Collection & Storage:** Google Forms & Sheets API
* **QR Code Generation:** QRCoder
* **Report Export:** PDFSharp / iTextSharp

---

## 🏗 Architecture Overview

CompList is built on a **layered architecture** for maintainability and scalability:

* **Presentation Layer:** User interface and interaction
* **Business Logic Layer:** Workflow rules, KPI calculations, and validation
* **Data Access Layer:** Communication with Google Sheets and local data sources

---

## ▶ Deployment & Usage

### 1. Clone the repository

```bash
git clone https://github.com/TrungDuongKhuu/CompList-task-manager.git
```

> ⚠️ **Note:** Google Service Account credentials (`*.json`) are **not included**.

### 2. Open the project

* Open `FinalProject.sln` in **Visual Studio 2022**
* Restore required NuGet packages and ensure compatible .NET Framework

### 3. Configure Google Service Account (Optional)

1. Create a Google Service Account in Google Cloud Console
2. Download the `.json` credential file
3. Place the file in:

```
FinalProject/bin/Debug/
```

4. Share the target Google Sheets/Form with the Service Account email (Editor access)

> Without this configuration, Google-based features will be unavailable; other functionalities remain operational.

### 4. Build & Run

* Build: `Ctrl + Shift + B`
* Run: `F5`

---

## 👨‍🎓 Academic Information

* **University:** Ton Duc Thang University (TDTU)
* **Faculty / Department:** Information Technology
* **Program:** Software Engineering
* **Academic Year:** 2024 – 2025
* **Instructor / Supervisor:** MSc Vo Hoang Quan

---

## 👥 Team & Roles

* **Khưu Trùng Dương** – **Project Manager & Tester**
  Coordinated the project, conducted system testing, and ensured quality.

* **Nguyễn Quốc Duy** – **Developer & Designer**
  Developed core features and user interface components.

* **Nguyễn Quang Trung** – **Software Developer & Designer**
  Implemented key functionalities and solved technical challenges.

* **Nguyễn Minh Nhựt** – **Tester & Designer**
  Performed testing, UI evaluation, and prepared documentation.

* **Huỳnh Kiến Đông Duy** – **Business Analyst & Developer**
  Conducted requirement analysis and contributed to development.

---

## 📌 Purpose & Scope

CompList was developed for **educational and practical purposes**, demonstrating desktop application development, API integration, workflow modeling, and KPI tracking in an enterprise context.


