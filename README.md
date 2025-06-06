# Relational-Data-Modelling-of-a-Centralized-Multi-Hospital-Patient-Management-System

# Centralized Multi-Hospital Patient Management System

![Healthcare Banner](https://img.shields.io/badge/Domain-Healthcare-blue?style=for-the-badge)  
![MySQL Badge](https://img.shields.io/badge/Tech-MySQL-green?style=for-the-badge)  
![Project Type](https://img.shields.io/badge/Type-Relational%20Data%20Modeling-yellow?style=for-the-badge)

## Overview

In a rapidly growing town in India, three government hospitals serve the majority of the population by offering affordable and accessible healthcare. However, patients often visit multiple hospitals depending on doctor availability, specialization, or treatment urgency — leading to fragmented records and inefficiencies in care delivery.

To address these challenges, this **Centralized Multi-Hospital Patient Management System** was designed as a relational database to:

-  Provide unified access to patient medical histories across hospitals.
-  Track diagnoses, prescriptions, appointments, and payments.
-  Standardize hospital operations and departments.
-  Offer data-driven insights for government healthcare policies.

---

## Technologies & Tools Used

- **MySQL** – For schema creation and querying  
- **ER Diagrams(Lucid Chart)** – Conceptual and physical design  
  
---

## Project Goals

- **Data Normalization** – To reduce redundancy and ensure consistency  
- **Cross-Hospital Coordination** – Shared doctor shifts, appointments, and patient histories  
- **Structured Reporting** – Support for dashboards and analytics  
  

---

## Functional Modules

### 1.  Patient Management
- Centralized repository for patient info, diagnoses, and prescriptions  
- Enables doctors to view complete patient history across hospitals  

### 2. Appointments & Payments
- Patients can book appointments with doctors in different hospitals  
- Each appointment is tied to a transparent payment record  

### 3. Hospital & Department Structure
- Hospitals have standard departments (e.g., Cardiology, Pediatrics)  
- Departments uniquely identified by `(hospital_id, department_id)`  

### 4. Doctor Scheduling
- Doctors work shifts across hospitals  
- Shift data managed for better workload balance  

### 5. Prescription & Inventory
- Records prescriptions per patient  
- Supports efficient pharmacy inventory based on prescription trends  

---

## Business Impact

                                                              

1. Improved Patient Care    :Doctors can access full medical history                   
2. Consistent Records       :Normalization prevents redundant data                     
3. Fast Reporting           :Standard schema for analytics                             
4. Efficient Staffing       :Shift tracking improves scheduling                        
5. Better Policy Planning   :Structured data supports decision-making                  






