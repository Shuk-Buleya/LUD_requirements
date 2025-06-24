**Software Requirements Specification**

---

**Project Title**: Local User Discount (LUD) Automation System


---

## 1. Introduction

### 1.1 Purpose

The purpose of this document is to outline the software requirements for automating the Local User Discount (LUD) process currently handled manually. The goal is to streamline form submissions, document verification, approval processes, card printing and distribution using a web-based information system.

### 1.2 Scope

The system will allow local users to apply for LUD through two pathways (this is just a suggestion, but the second option can be left out ofr now):

* **Option 1**: Traditional paper-based submission for individuals who are not tech-savvy or literate, handled by Office Assistants who digitize the documents i.e scanning and uploading the DOCs.
* **Option 2**: Full online submission by users with internet access and technical literacy.

### 1.3 Acronyms

* **LUD**: Local User Discount
* **RFA**: Roads Fund Administration
* **SO**: Station Officer
* **OA**: Office Assistant

---

## 2. Functional Requirements

### 2.1 User Application Module

#### Option 1: Paper-based Submission for Non-tech Users

* **2.1.1**: Office Assistants shall provide physical LUD forms to users who prefer manual submission.
* **2.1.2**: Local users shall fill in the paper forms and attach the required documents.
* **2.1.3**: Office Assistants shall scan and upload the completed application form and attachments into the system.
* **2.1.4**: The system shall record the name of the user, date of submission and scanned document files.

#### Option 2: Digital Submission for Tech-savvy Users

* **2.1.5**: Users shall fill and submit LUD application forms online.
* **2.1.6**: The system shall allow uploading of supporting documents (village head letter, bluebook, utility bill).
* **2.1.7**: Users shall be able to track the status of their applications.


### 2.2 Eligibility Evaluation

* **2.2.1**: Station Officers shall be able to view, verify, approve or reject applications with comments.

### 2.3 Physical Verification Coordination

* **2.3.1**: Station Officers shall assign Toll Supervisors to applications.
* **2.3.2**: Toll Supervisors shall submit verification reports.
* **2.3.3**: Anomalies shall be flagged and sent for re-review.

### 2.4 Director Approval and IT Processing

* **2.4.1**: Tolling Director shall approve or reject verified applications.
* **2.4.2**: The system shall send card print requests to the IT department.

### 2.5 Card Printing and Tracking

* **2.5.1**: IT shall update the card status (Printed, Delivered).
* **2.5.2**: Station Officers shall confirm card receipt (card status shall be updated to ready).

### 2.6 Card Distribution

* **2.6.1**: Office Assistants shall distribute cards and mark collection in a digital register.
* **2.6.2**: Local Users shall digitally sign upon collection.
* **2.6.3**: Users shall be notified via SMS/email when cards are ready.

### 2.7 Reporting and Auditing

* **2.7.1**: The system shall generate reports on application status, approvals, distributions, etc.
* **2.7.2**: The system shall maintain audit logs of all user actions.

### 2.8 Access Control

* **2.8.1**: Role-based access for different users (Local User, OA, SO, Supervisor, Director, IT, Admin).
* **2.8.2**: Each role shall access only authorized sections and data.

### 2.9 System Requirements

* **2.9.1**: The system shall be mobile responsive.
* **2.9.2**: The system shall store documents securely with restricted access.
---

## 3. Non-Functional Requirements

### 3.1 Performance Requirements

* The system shall support up to 100 concurrent users.

### 3.2 Security Requirements

* All data shall be encrypted in transit (HTTPS) and at rest.
* Role-based access control and audit logs shall be enforced.

### 3.3 Usability Requirements

* The system shall have a user-friendly interface with form validation

### 3.4 Availability

* The system shall be available 99% of the time excluding scheduled maintenance.

---



---

