# **CompList – Work Checklist & Performance Tracking Platform**

**CompList** is a desktop application developed on the **C# .NET WinForms** platform, focusing on supporting organizations in managing work checklists, supervising task execution, and evaluating employee performance. The system is designed to reduce manual reporting, increase transparency, and standardize operational processes across departments.

The application adopts a **QR-based reporting approach** combined with **Google Forms and Google Sheets**, allowing employees to submit task results quickly while enabling managers to monitor progress and KPIs in a centralized environment.

---

## 🔍 System Overview

CompList provides an end-to-end workflow for checklist management, from checklist creation and task assignment to data collection, reporting, and performance analysis. The system is suitable for enterprises, departments, and project-based teams that require regular task verification and structured reporting.

---

## ⚙ Functional Modules

### 1. Checklist Configuration

* Create and maintain structured work checklists
* Define checklist titles, descriptions, and task items
* Assign responsibilities to employees or teams
* Classify checklists by department, project, or execution period

### 2. QR Code–Driven Task Execution

* Automatically generate QR codes linked to individual checklists
* Manage and archive QR codes for recurring or one-time tasks
* Deploy QR codes at work locations for easy employee access

### 3. Data Submission & Synchronization

* Employees scan QR codes to access Google Forms
* Task completion data and feedback are stored in Google Sheets
* The application periodically retrieves and processes submitted data
* Checklist status is updated based on synchronized results

### 4. User Roles & Access Control

* **System Administrator:** Full access to configuration, data, and reports
* **Department Supervisor:** Manage checklists, assign tasks, review results
* **Employee:** Execute tasks and submit completion feedback
* **External Personnel:** Limited access according to assigned permissions

### 5. Reporting & KPI Evaluation

* Generate structured reports in **PDF** and **Excel** formats
* Automatically include department names, timestamps, and pagination
* Filter and analyze reports by department, checklist status, or time range
* Evaluate KPIs such as completion rate, delay frequency, and workload distribution
* Email notifications for pending or overdue checklist items

---

## 🧪 Technology Stack

* **Programming Language:** C#
* **Framework:** .NET WinForms
* **Data Collection:** Google Forms
* **Data Storage & Processing:** Google Sheets API
* **QR Code Generation:** QRCoder
* **Report Export:** PDFSharp / iTextSharp

---

## 🧱 Software Architecture

The project is organized following a **layered architecture model** to enhance maintainability and scalability:

* **Presentation Layer:** Handles user interface and interaction
* **Business Logic Layer:** Implements workflow rules, KPI calculation, and validation
* **Data Access Layer:** Manages communication with Google Sheets and local data sources

---

Dưới đây là **phiên bản TIẾNG ANH – chuẩn README / report – an toàn về bảo mật**, bạn có thể **copy dùng trực tiếp** 👌

---

## ▶ Deployment & Execution

### 1. Clone the source code

```bash
git clone https://github.com/TrungDuongKhuu/CompList-task-manager.git
```

> ⚠️ **Note**: For security reasons, the Google Service Account credential file (`*.json`) is **not included** in the public repository.

---

### 2. Open the solution

* Open `FinalProject.sln` using **Visual Studio 2022**
* Make sure the following requirements are installed:

  * Compatible **.NET Framework**
  * All **NuGet packages** are successfully restored

---

### 3. Configure Google Service Account (Required for Google-based features)

The application integrates with **Google Sheets / Gmail APIs** using a **Google Service Account**.

To enable these features:

1. Create a **Google Service Account** in Google Cloud Console
2. Download the credential file in `.json` format
3. Place the credential file into the application runtime directory:

```
FinalProject/bin/Debug/
```

4. Rename the file to match the configuration in the source code, for example:

```
quanlychecklist-440716-1c38989239d9.json
```

5. Share the target Google Sheet / Form with the Service Account email and grant **Editor** permission

> If this configuration is not provided, Google-related features (Sheets, Gmail, Forms) will be unavailable, while **other core functionalities of the application remain fully operational**.

---

### 4. Build and run the application

* Build the project: `Ctrl + Shift + B`
* Run the application: `F5`

---

Tốt 👍 mình sẽ **viết lại phương án 2**, giữ văn phong **học thuật – chuyên nghiệp**, đồng thời **diễn đạt khéo cho thành viên “ngoài rìa”** (làm báo cáo) để **không bị yếu vai trò** khi giáo viên hay nhà tuyển dụng đọc.

Dưới đây là **bản hoàn chỉnh**, bạn có thể **dán thẳng vào README / báo cáo**.

---

OK 👍 mình đã **chuyển toàn bộ thông tin bạn cung cấp** thành **một đoạn trình bày chuẩn học thuật – chuyên nghiệp**, phù hợp để dùng trong **README, báo cáo đồ án hoặc phụ lục thông tin nhóm**.
Mình **không liệt kê email/sđt quá thô**, mà lồng ghép gọn gàng, đúng ngữ cảnh dự án.

---

Hoàn toàn được 👍 — thông tin **trường, năm học, môn học** là rất hợp lý để đưa vào README / báo cáo đồ án, giúp người đọc **biết bối cảnh học thuật của dự án**.
Bạn có thể thêm **trước phần Team Composition**, ví dụ:

---

## 👨‍🎓 Academic Information

* **University:** Ton Duc Thang University (TDTU)
* **Department:** Faculty of Information Technology
* **Academic Year:** 2025 – 2026
* **Course / Subject:** Software Engineering
* **Instructor:** MSc Vo Hoang Quan

---

## 👥 Team Composition and Responsibilities

* **Khưu Trùng Dương (me)** – **Project Manager & Tester**
  Responsible for project coordination, task planning, system testing, quality assurance, and overall progress control of the project.

* **Nguyễn Quốc Duy** – **Developer & Designer**
  Contributed to software development, feature implementation, and user interface design, focusing on usability and visual consistency.

* **Nguyễn Quang Trung** – **Software Developer & Designer**
  Participated in application development, core feature implementation, and technical problem-solving during the development process.

* **Nguyễn Minh Nhựt** – **Tester & Designer**
  Responsible for system testing, UI evaluation, and preparation of project documentation and reports.

* **Huỳnh Kiến Đông Duy** – **Business Analyst & Developer**
  Conducted requirement analysis, supported system design from a business perspective, and contributed to application development.

---


## 📌 Purpose & Scope

This project was developed for **educational and practical research purposes**, emphasizing enterprise workflow modeling, API integration, and desktop application development using a structured software architecture.

Business Logic Layer: Implements workflow rules, KPI calculation, and validation

Data Access Layer: Manages communication with Google Sheets and local data sources
