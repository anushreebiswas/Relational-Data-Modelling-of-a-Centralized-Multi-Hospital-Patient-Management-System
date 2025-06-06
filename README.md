# Relational-Data-Modelling-of-a-Centralized-Multi-Hospital-Patient-Management-System
Relational Data Modelling of a Healthcare System

##### Centralized Multi-Hospital Patient Management System
##### Project Type: Relational Data Modeling & SQL Implementation
##### Tools Used: MySQL, ER Diagrams (Conceptual + Physical Models), Normalization
##### Domain: Public Health / Healthcare IT

##### Overview
In a rapidly growing town in India, three government hospitals serve the majority of the population by offering affordable and accessible healthcare. However, patients often visit multiple hospitals depending on doctor availability, specialization, or treatment urgency — leading to fragmented records and inefficiencies in care delivery.To address these challenges, the Centralized Multi-Hospital Patient Management System was designed. The goal is to:

1. Provide unified, real-time access to patient medical histories across hospitals.

2. Ensure accurate tracking of diagnoses, prescriptions, appointments, and payments.

3. Enable better coordination among doctors, departments, and pharmacies.

4. Offer data-driven insights for government healthcare policy planning.

  
##### Requirements Breakdown

##### 1. Patient Management

Maintain a centralized database of patient demographics, diagnoses, and prescribed medications.

Enable doctors to access a patient’s entire medical history regardless of hospital location.

##### 2. Appointments & Payments

Patients can book appointments with doctors in different hospitals.

Each appointment is linked to a payment record to ensure transparency and aid government subsidies/audits.

##### 3. Hospital & Department Structure

All hospitals share a standardized set of departments (e.g., Cardiology, Pediatrics).

Departments are uniquely identified via a combination of Hospital_id + Department_id.

##### 4. Doctor Scheduling & Shifts

Doctors are assigned to different shifts and can work across multiple hospitals.

Shift data is maintained to ensure proper workload balancing and staffing.

##### 5. Prescription & Inventory Management

Track prescribed medicines for each patient.

Optimize hospital pharmacy inventory based on prescription trends.

##### Business Impact:

a. Improved Patient Outcomes through better data linkage and insight into treatment histories.

b. Reduced Data Redundancy and inconsistencies via normalization.

c. Faster Reporting and dashboarding using standardized schema.

d. Better Resource Management across shifts, hospitals, and departments.

e. Enhanced Decision Making with reliable and analyzable structured data.


