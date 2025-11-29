# 📄 README – Hospital Database Normalization

# I am Prabhashankar Mishra.

This project normalizes an unstructured hospital appointment table into **1NF, 2NF, and 3NF**.
I removed repeating groups (Medications), eliminated partial dependencies, and resolved transitive dependencies.
The final design produces a fully normalized 3NF database with clear primary and foreign keys.

### **Final Tables Created**

1. **Doctor(DoctorID, DoctorName, DoctorSpecialization)**
2. **Patient(PatientID, DoctorID, PatientName, PatientPhone, PatientCity)**
3. **Appointment(AppointmentID, PatientID, AppointmentDate)**
4. **Medication(MedicationID, AppointmentID, MedicationName)**

The final schema ensures data consistency, avoids redundancy, and supports efficient querying.
