# Clinical-Management
Introduction

This document provides an overview for a dental clinic management system. The ERD models various entities, their attributes, and relationships, covering patient records, appointments, financial transactions, staff roles, and inventory management.

Entities and Relationships

1. Patient Management

Patient: Stores details like name, DOB, SSN, ID code, blood type, and medical history.

Dental History: Tracks dental-related conditions (e.g., TMJ, gum health, medications, allergies, diseases, past treatments, etc.).

Appointment: Records diagnosis, symptoms, status, and feedback related to patient visits.

Prescription: Contains details such as medication name, dosage, days, and times to be taken.

2. Staff and Employee Management

Doctor: Includes qualifications, salary, and works in a specific department.

Secretary: Tracks name, DOB, salary, and department.

Employee: General entity for staff, including hire date, qualification, resignation, and salary details.

Departments: Groups doctors and other staff into units.

3. Financial Transactions

General Ledger: Manages payables and receivables.

Payables & Receivables: Store financial transaction details.

Received & Paid: Represent increases and decreases in financial transactions.

4. Attendance and Leave Management

Leaves: Stores employee leave records, including reason, date, and status.

Absence: Tracks employee absences by date and time.

Holidays: Stores official holiday dates and names.

5. Inventory and Laboratory Management

Laboratory: Tracks laboratory orders and their status.

Stock: Maintains inventory details, including item name, brand, quantity, and unit price.

Order Item: Represents items ordered, along with quantity and pricing.

Relationships Summary

A Patient has multiple Appointments.

A Doctor works in a Department.

A Doctor can issue multiple Prescriptions.

Employees can take Leaves and have Absences recorded.

General Ledger manages Payables and Receivables.

Laboratory orders involve Stock items and Order Items.

Conclusion

This ERD provides a structured view of how different components of the dental clinic interact. It supports efficient patient management, financial tracking, employee management, and inventory control.

