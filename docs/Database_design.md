# Database Design

## Overview

EduReportCard Cloud uses a multi-school database architecture. Every record belongs to a specific school using a unique School ID.

---

## Collections

### Schools

- School ID
- School Name
- Motto
- Logo
- Address
- Region
- Division
- Phone
- Email
- Principal Name
- Subscription Plan
- Subscription Status
- Expiry Date
- Date Registered

---

### Users

- User ID
- School ID
- Full Name
- Email
- Phone
- Role
- Status
- Last Login

Roles:
- Super Admin
- School Admin
- Teacher
- Parent
- Student

---

### Students

- Student ID
- School ID
- Admission Number
- Full Name
- Gender
- Date of Birth
- Class
- Parent ID
- Photo
- Status

---

### Teachers

- Teacher ID
- School ID
- Full Name
- Email
- Phone
- Subjects
- Classes

---

### Subjects

- Subject ID
- School ID
- Subject Name
- Subject Code
- Coefficient
- Assigned Teacher

---

### Examinations

- Exam ID
- School ID
- Academic Year
- Term
- Exam Type
- Date

---

### Results

- Result ID
- Student ID
- Subject ID
- Marks
- Grade
- Average
- Position
- Teacher Remark
- AI Remark

---

### Other Collections

- Parents
- Attendance
- Fees
- Subscriptions
- Announcements
- Library
- Hostel
- Settings
- AuditLogs
- AIReports
