# EmployeePunching

# EmployeePunchingSystem

## Project Overview
The Employee Management Application is a web-based application developed to manage employee attendance and related activities in one centralized system.
The application allows employees to punch in and punch out, apply for leave, submit attendance ratification requests, and view their attendance records.
It also provides approval workflows for authorized employees to manage leave and ratification requests. Administrators can manage company holidays and weekly off configurations.
The main objective of this application is to simplify employee management, reduce manual work, and maintain attendance and leave records efficiently.

## Key Features
**Employee Registration:** New employees can create their accounts.
**Secure Login:** Employees can log in using their employee number and password.
**Change Password:** Existing employees can update their passwords.
**Punch In / Punch Out:** Records employee attendance and working hours.
**Attendance Status:** Displays employee attendance summaries.
**Leave Management:** Employees can apply for leave and view their leave history.
**Leave Approval:** Authorized employees can approve or reject leave requests.
**Ratification Request:** Employees can submit requests to correct attendance-related issues.
**Ratification Approval:** Approvers can review and process ratification requests.
**Holiday Master:** Administrators can add, edit, and delete company holidays and weekly offs.
**Punching Records:** Allows users to search attendance records using a date range.
**Role-Based Access:** Provides access to application modules based on user roles and permissions.

## Application Modules
    |Module|                                |Description |
| Login                          | Employee authentication |
| Registration                   | Create employee accounts |
| Dashboard                      | Access application modules |
| Attendance Status              | View attendance summary |
| Leave Management               | Apply for leave and view history |
| Leave Approval                 | Approve or reject leave requests |
| Ratification                   | Submit attendance correction requests |
| Ratification Approval          | Review and process requests |
| Holiday Master                 | Manage holidays and weekly offs |
| Punching Records               | Search and view attendance details |

## Approval Workflow
The application follows a designation-based approval hierarchy.
- Engineer → Senior Engineer
- Senior Engineer → Team Leader
Approvers can review requests, provide comments, and approve or reject them.

## Technologies Used
**Frontend:**
- React.js
- JavaScript
- HTML
- CSS
- Axios
**Backend:**
- Java
- Spring Boot
- Spring Data JPA
- Spring Security
- REST APIs
**Database:**
- MySQL / MariaDB

**Tools:**
- Visual Studio Code
- HeidiSQL
- Git and GitHub


## Project Benefits
- Reduces manual attendance management.
- Maintains centralized employee records.
- Simplifies leave and ratification approval processes.
- Improves transparency through request status tracking.
- Makes attendance information easier to access.
- Provides organized holiday and weekly off management.

## Conclusion
The Employee Management Application provides a centralized solution for managing employee attendance, leave requests, ratification requests, and holiday configurations.
It simplifies daily employee management activities through an organized interface, automated workflows, validations, and role-based access.
