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

## 3. Main Entities(Tables)

### Patient
Stores information about patients.
Like
. Patient ID
. Name
. Age
. Gender
. Phone number

### Doctor
Stores information about doctors.
Like
. Doctor ID
. Name
. Specialization
. Phone number

### Appointment
Stores information about appointments between patients and doctors.
Like
. Appointment ID
. Patient ID
. Doctor ID
. Appointment date
. Appointment time

### Room
Stores information about hospital rooms.
Like
. Room ID
. Room number
. Room type
. Availability

### Admission
Stores information about patients who are admitted to the hospital.
Like
. Admission ID
. Patient ID
. Room ID
. Admission date


### Nurse
Stores information about nurses working in the hospital.
Like
. Nurse ID
. Name
. Department
. Phone number

### Medical Info
Stores information about medicines and medical supplies.
Lil baby
. Medicine ID
. Medicine name
. Quantity
. Price



## 4. Database Relationships

The tables are connected using relationships.

EG:

**Patient -> Appointment <- Doctor**

A patient can have multiple appointments, and a doctor can have multiple appointments.

**Patient -> Admission -> Room**

A patient can be admitted to a room.

Primary keys and foreign keys are used to connect the tables.



## 5. SQL Commands We will use

Below are some of the SQL commands we gonna use on this project:

CREATE TABLE;
INSERT;
SELECT;
UPDATE;
DELETE;
ALTER TABLE;

# 6. Benefits 

. Reduces paperwork
. Organize info
. Make records easier to find
.Improves data organization


# 7. Conclusion

The hospital management system is a useful SQL database project coz it shows how a real life hospital can sort and manage complex info.
