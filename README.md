# 📚 Smart Library Request Workflow

**Developed by:** 
**1. Name:** SYED MOHAMMAD SAMEER  

**Roll No.:** 23HM1A3354

**2. Name:**  

**Roll No.:** 

**3. Name:**  

**Roll No.:** 

**4. Name:**  

**Roll No.:** 

**5. Name:**  

**Roll No.:** 

**college:** ANNAMACHARYA INSTITUTE OF TECHNOLOGY AND SCIENCES

**Internship:** SmartBridge × ServiceNow SkillWallet Internship  
**Project:** Smart Library Request Workflow  
**Platform:** ServiceNow  
**Project Type:** Enterprise Workflow Automation Application (Low-Code/No-Code)  
**Date:** 27 June 2026

---

# 📖 Introduction

The **Smart Library Request Workflow** is a role-based Library Management System developed on the **ServiceNow Platform**. The application automates the complete library borrowing process by allowing students to request books online while enabling librarians to manage inventory, approve requests, and monitor borrowing activities.

The solution replaces manual book management with automated workflows, role-based security, and real-time reporting, improving operational efficiency, transparency, and user experience.

---

# 🎯 Business Objectives

- Automate the library book borrowing process.
- Reduce manual paperwork and approval delays.
- Improve inventory tracking and book availability.
- Secure library operations using Role-Based Access Control (RBAC).
- Generate reports for better decision-making.
- Provide an efficient and user-friendly library management solution.

---

# ✨ Key Features

- 📚 Book Inventory Management
- 👨‍🎓 Student Borrow Requests
- 👨‍💼 Librarian Approval Workflow
- 🔄 Automated Flow Designer Workflow
- 🔐 Role-Based Access Control (ACL)
- 🎨 Dynamic UI Policies
- 📊 Reports & Dashboards
- 📧 Email Notifications
- ✅ Reference Qualifier for Available Books
- 🧪 End-to-End Testing & Validation

---

# 🔄 Workflow Overview

```text
Student Login
      │
      ▼
Browse Available Books
      │
      ▼
Submit Borrow Request
      │
      ▼
Borrow Request Created
      │
      ▼
Flow Designer Trigger
      │
      ▼
Librarian Approval
      │
 ┌────┴────┐
 │         │
Approved  Rejected
 │         │
 ▼         ▼
Book Issued  Request Closed
 │
 ▼
Email Notification
 │
 ▼
Book Returned
 │
 ▼
Book Status Updated
```

---

# 🏗️ Project Architecture

```text
                Student
                   │
                   ▼
          Borrow Request Form
                   │
                   ▼
          Borrow Request Table
                   │
                   ▼
            Flow Designer Flow
                   │
         ┌─────────┴─────────┐
         ▼                   ▼
   Approval Task         Reject Request
         │
         ▼
     Librarian
         │
         ▼
 Update Book Status
         │
         ▼
Update Borrow Request
         │
         ▼
 Email Notification
         │
         ▼
Reports & Analytics
```

---

# 📂 Project Structure

```text
Smart-Library-ServiceNow
│
├── Documentation/
│   ├── Phase 1 Requirement Analysis & Planning
│   ├── Phase 2 Backend Development & Configurations
│   ├── Phase 3 UI/UX Development & Customization
│   ├── Phase 4 Data Migration, Testing & Security
│   ├── Phase 5 Deployment, Documentation & Presentation
│   └── Project Conclusion
│
├── screenshots/
│
├── flow-designer/
│
├── tables/
│
├── variables/
│
├── ui-policy/
│
├── acl/
│
├── reports/
│
├── exports/
│
├── demo-video/
│
├── README.md
├── LICENSE
└── .gitignore
```

---

# 🛠️ Technology Stack

| Technology | Purpose |
|------------|----------|
| ServiceNow | Enterprise Platform |
| Flow Designer | Workflow Automation |
| Custom Tables | Data Storage |
| ACL | Role-Based Security |
| UI Policies | Dynamic Form Behaviour |
| Reference Qualifiers | Data Validation |
| Reports | Analytics |
| Email Notifications | User Communication |

---

# 📋 Database Tables

## 📚 Book Table (`u_book`)

Stores library inventory.

### Fields

- Book ID
- Title
- Author
- ISBN
- Category
- Total Copies
- Status

Status Values

- Available
- Issued
- Lost

---

## 📖 Borrow Request Table (`u_borrow_request`)

Stores borrowing transactions.

### Fields

- Requested By
- Book
- Request Date
- Return Date
- Status

Status Values

- Requested
- Approved
- Rejected
- Returned

---

# 🔐 Security Features

- Student Role
- Librarian Role
- Role-Based Access Control (RBAC)
- Access Control Lists (ACLs)
- Reference Qualifier
- UI Policies
- Form Validation

---

# 📊 Reports

The application provides reports including:

- 📈 Most Borrowed Books
- 📚 Active Borrow Requests
- 📊 Borrowing Trends
- 📉 Book Availability

---

# 📁 Documentation

Complete documentation includes:

- Business Objectives
- Functional Scope
- Stakeholder Mapping
- Execution Roadmap
- Automation Logic
- Data Architecture
- Navigation Flow
- Usability
- Security Architecture
- Access Control
- Report Creation
- Deployment & Validation
- Technical Documentation
- Demo Planning
- Project Conclusion

---

# 🧪 Testing

The application was validated using:

- Student request submission
- Librarian approval
- Book status updates
- Email notification testing
- ACL verification
- UI Policy testing
- Report validation

---

# 🚀 Future Enhancements

- 📱 Mobile Application
- 📚 Digital Library Integration
- 🔍 QR Code / Barcode Support
- 💰 Fine Management
- ⏰ Automatic Overdue Notifications
- 📊 Advanced Dashboards
- 🤖 AI-Based Book Recommendations
- 🌐 REST API Integration

---

# 📸 Screenshots

The repository contains screenshots for:

- Roles
- Tables
- Fields
- Flow Designer
- UI Policies
- ACLs
- Reports
- Forms
- Testing

---

# 🎥 Demo

The complete demonstration video is available in the **demo-video** folder.

---

# 📄 License

This project was developed as part of the **SmartBridge × ServiceNow SkillWallet Internship** for educational purposes.

---

## 👨‍💻 Author

**SYED MOHAMMAD SAMEER**

**B.Tech – Computer Science & Engineering (AI & ML)**

**ServiceNow SkillWallet Internship Project**

---

## ⭐ Project Status

**Status:** ✅ Completed

**Platform:** ServiceNow

**Project Type:** Enterprise Workflow Automation Application

**Development Model:** Low-Code / No-Code

**Last Updated:** 04 July 2026
