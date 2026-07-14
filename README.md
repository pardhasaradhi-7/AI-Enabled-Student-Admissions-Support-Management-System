# AI-Enabled-Student-Admissions-Support-Management-System
Salesforce AI-enabled student admission management system using Lightning, Flows, Approval Processes, and Agentforce.

# AI-Enabled Student Admissions & Support Management System

## Project Overview

The AI-Enabled Student Admissions & Support Management System is a Salesforce-based application designed to streamline student admission processes using automation, AI-driven insights, and secure role-based access.

The system helps admission counselors and managers to analyze student applications, prioritize admissions, manage enrollment approvals, and make better decisions using AI recommendations.

---

## Objectives

- Build an AI-assisted student admission management platform
- Automate admission workflows using Salesforce Flows
- Provide AI-based student prioritization and risk analysis
- Improve discount approval processes
- Reduce manual admission effort
- Provide secure access based on user roles and profiles

---

# Salesforce Implementation

## 1. Data Model

Created and configured Salesforce objects:

### Custom Object

### Student Enrollment (Student_Enrollment__c)

Used to manage student admission and enrollment details.

Fields created:
- Student
- Course
- Enrollment Date
- Discount Percentage
- Enrollment Status
- Approval Status
- Payment Status
- AI Priority Score
- Risk Level
- Discount

---

## Standard Objects Used

### Contact (Student)
Used to store student information.

### Course__c
Used to maintain available courses.

### Account
Used for organization-related information.

### Opportunity
Used for admission opportunity tracking.

### Task
Used for follow-ups and reminders.

---

# 2. Salesforce Lightning App

Created Lightning Application:

**AI-Enabled Student Admissions & Support Management System**

Added navigation items:

- Accounts
- Contacts
- Student Enrollment
- Course
- Opportunity

Configured app access for System Administrators and admission users.

---

# 3. Page Layouts & UI Customization

Customized Page Layouts for:

- Student Enrollment
- Course
- Account
- Contact
- Opportunity

Configured fields and improved user experience.

Created Lightning Record Pages and Dynamic Forms to display important student information.

---

# 4. User Management & Security

Created Roles:

- Admission Manager
- Admission Counselor

Created Profiles:

- Admission Manager Profile
- Admission Counselor Profile

Configured:

- Object permissions
- Field-level security
- Role-based access control

Users created:

- Admission Counselor User
- Admission Manager User

---

# 5. Duplicate Management

Implemented duplicate prevention using:

## Matching Rules

Created:

- Unique Student - Email & Phone
- Unique Enrollment - Student & Course

## Duplicate Rules

Created:

- Unique Student Email and Phone
- Unique Student Course Enrollment

This prevents duplicate student and enrollment records.

---

# 6. Automation Using Salesforce Flows

Implemented automation using:

- Record Triggered Flows
- Scheduled Flows
- Screen Flows

Automation helps in:

- Updating records automatically
- Sending notifications
- Supporting admission workflows
- Reducing manual tasks

---

# 7. Approval Process

Configured approval workflow for:

- High discount enrollment requests
- Admission decision approvals

Admission Managers can review and approve/reject requests.

---

# 8. AI & Agentforce Implementation

Implemented AI-driven features:

## AI Priority Score

Helps identify high-priority student applications.

## Risk Analysis

Identifies possible enrollment risks.

## Discount Approval Guidance

Provides recommendations for discount decisions.

## Agentforce

Created Admissions Assistant Agent to support:

- Student Application Summary
- Enrollment Risk Analysis
- Discount Approval Guidance
- Admission Recommendations

---

# 9. Validation & Testing

Performed testing for:

- Student record creation
- Enrollment creation
- Duplicate record detection
- Approval workflow
- User access
- Automation execution

---

# Technologies Used

- Salesforce Lightning Platform
- Salesforce Flow Builder
- Lightning App Builder
- Dynamic Forms
- Approval Processes
- Agentforce
- Prompt Builder
- Salesforce Security Model

---

# Business Benefits

The system provides:

- Faster admission processing
- Better student prioritization
- Reduced manual effort
- Improved approval efficiency
- AI-assisted decision making
- Better admission team productivity

---

# Future Enhancements

- Advanced AI prediction models
- Student chatbot integration
- Automated communication with applicants
- Advanced analytics dashboards
- Mobile admission support

---

## Author

Pardha Saradhi Jonnadula

B.Tech Computer Science Engineering
