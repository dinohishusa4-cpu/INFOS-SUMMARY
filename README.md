# Hospital Management System

## 1. Introduction

A Hospital Management System is a database system used to manage the daily operations and information of a hospital.

It helps store and organize information about patients, doctors, rooms, appointments, admissions, nurses, and medical supplies.

---

## 2. Purpose of the System

The main purpose of a Hospital Management System is to:

. Store patient information
. Manage doctor information
. Manage patient appointments
. Keep track of hospital rooms
. Record patient admissions and discharges
. Manage nurses and medical staff
. Keep track of medical supplies
. Make information easier to access and manage

---

## 3. Main Entities / Tables

### Patient
Stores information about patients.

Examples:
- Patient ID
- Name
- Age
- Gender
- Phone number

### Doctor
Stores information about doctors.

Examples:
- Doctor ID
- Name
- Specialization
- Phone number

### Appointment
Stores information about appointments between patients and doctors.

Examples:
- Appointment ID
- Patient ID
- Doctor ID
- Appointment date
- Appointment time

### Room
Stores information about hospital rooms.

Examples:
- Room ID
- Room number
- Room type
- Availability

### Admission
Stores information about patients who are admitted to the hospital.

Examples:
- Admission ID
- Patient ID
- Room ID
- Admission date

### Discharge
Stores information about patients when they leave the hospital.

Examples:
- Discharge ID
- Patient ID
- Discharge date
- Discharge summary

### Nurse
Stores information about nurses working in the hospital.

Examples:
- Nurse ID
- Name
- Department
- Phone number

### Medical Store
Stores information about medicines and medical supplies.

Examples:
- Medicine ID
- Medicine name
- Quantity
- Price

---

## 4. Database Relationships

The tables are connected using relationships.

For example:

**Patient → Appointment ← Doctor**

A patient can have multiple appointments, and a doctor can have multiple appointments.

**Patient → Admission → Room**

A patient can be admitted to a room.

Primary keys and foreign keys are used to connect the tables.

---

## 5. SQL Commands Used

Some SQL commands that can be used in this project include:

```sql
CREATE TABLE;
INSERT;
SELECT;
UPDATE;
DELETE;
ALTER TABLE;
