# Medical Diagnosis Center by Service Portal (ServiceNow)

**Student Name:** Mohammed Jasmine
**Roll No:** 23HT1A0592
**Email:** 23ht1a0592@city.ac.in
**Mentor:** Hazari Ajay Kumar Kumar
**Platform:** ServiceNow - Service Portal

## 1. Project Overview
The Medical Diagnosis Center by Service Portal (ServiceNow) project focuses on developing a digital healthcare service portal to manage patient services, appointments, diagnostic requests, and medical records efficiently.

The solution enables patients to submit service requests, track appointment status, access diagnostic information, and communicate with healthcare teams through a user-friendly ServiceNow Service Portal interface.

It improves healthcare service delivery by automating workflows, managing requests, and providing better coordination between patients, doctors, and support staff.

## 2. Project Structure

Medical-Diagnosis-Center/
  ├── README.md  <- Main Documentation
  ├── docs/
  │     └── Documentation.pdf  <- Full Detailed Documentation
  └── screenshots/
        └── portal.png

## 3. Problem Statement
In hospitals, managing appointments manually leads to time waste, double bookings, and missing records. To solve this, a centralized digital portal is required.

## 4. Objectives
- To book patient appointments digitally
- To track diagnostic requests
- To improve coordination between Patient, Doctor, and Support Staff
- To reduce manual work through workflow automation
- To store medical records securely

## 5. Skills Required
Development Management, Admin Tools, Portal Servers, HTML Application, CSS Codes, JS API, XML Concepts, JSON

## 6. Project Phases
**Phase 1: Requirement Analysis & Planning**
Complexity: Medium, Duration: 1h 0m, Progress: 90%, Stories: 4

**Phase 2: Backend Development & Configurations**
Created Tables, Fields, Forms, and Choice Lists.

**Phase 3: UI/UX Development & Customization**
Designed Service Portal, Widgets, and a user-friendly interface.

**Phase 4: Data Migration & Security**
Applied data validation, role-based access, and security rules.

**Phase 5: Deployment, Documentation & Final Presentation**
Testing, Documentation, and Final Demo.

**Project Progress:** 84%

## 7. System Architecture & Tables
**1. Appointment Table**
Manages appointments with fields like Patient Details, Doctor, Appointment Date, Slot Time, Status, and Payment Status.

**2. Diagnostic Request Table**
Tracks diagnostic tests requested by the patient, their status, and reports.

Structured Table Relationships were used between tables, which reduced data duplication.

## 8. Key Features
- Online Appointment Booking
- Slot Time Selection
- Appointment Status Tracking - New, Approved, Rejected, Completed
- Diagnostic Request Submission
- Service Portal for Patients
- Automated Workflow Approvals
- Role-Based Access

## 9. Security & Access Control
- Implemented role-based security design
- Users can only see the data they are authorized to access
- Tested access using Debug Security Rules
- Followed minimal hardcoding practice

## 10. Monitoring & Troubleshooting
Used Flow Execution Details to monitor workflow performance. To identify failed actions, used System Logs, gs.info() debugging, GlideRecord trace analysis, Service Portal preview tools, and Debug Security Rules.

This helped to accurately validate data flow, automation triggers, and role-based access.

## 11. Scalability & Maintainability
Designed reusable components - Modular widgets, Reusable Script Includes, Configurable Flow Designer actions.

**ServiceNow Best Practices Followed:**
- Scoped application development
- Proper naming conventions
- Role-based security design
- Minimal hardcoding
- Structured table relationships

**Future Enhancements:**
- Integration with external payment gateways
- SMS notifications
- Doctor portal integration
- Analytics expansion

## 12. Testing
- Tested whether all fields in the form are saving correctly
- Checked whether Choice Lists - Slot Time, Payment Status are working correctly
- Tested from patient view in Portal preview
- Checked whether workflow triggers and status changes correctly

## 13. Resources Used
**1. SkillWallet Platform Instructions**
Completed the project by following the project instructions, phases, stories, and subtasks given in SkillWallet. For each phase, implemented as per the instructions provided there.

**2. ServiceNow Official Documentation**
Took reference from ServiceNow docs for Tables, Service Portal, Widgets, and Flow Designer.

**3. ServiceNow Developer Instance (PDI)**
Used ServiceNow PDI for practice and development.

**4. Mentor Guidance**
Completed the project by clearing doubts with the guidance of Mentor Hazari Ajay Kumar Kumar.

## 14. Conclusion
Through this project, I practically learned ServiceNow Service Portal, Tables, Workflows, and Security. I made the hospital appointment process simple, fast, and secure. This system can be further expanded in the future with payment, SMS, and doctor portal integration.
