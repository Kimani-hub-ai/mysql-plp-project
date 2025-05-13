# mysql-plp-project
# Clinic Database Management System

## Project Title: Clinic Booking System Database

### Description:

This project implements a **Clinic Booking System** using a MySQL relational database. The system manages:

* Patients' details (Name, Email, Phone, etc.)
* Doctors' information (Name, Specialty, Department)
* Appointment scheduling and tracking
* Medical records for patients
* Prescriptions linked to appointments

### Features:

* 1\:Many relationship between `Doctors` and `Appointments`
* 1\:Many relationship between `Patients` and `Appointments`
* Many\:Many relationship for `Appointments` and `Prescriptions`
* 1:1 relationship between `Patients` and `Medical Records`
* Structured schema for clinic management

### How to Run/Setup:

1. Install MySQL or use a service like **XAMPP** or **MAMP**.
2. Create a new database named `ClinicDB` in your MySQL environment.
3. Copy and paste the `clinic_db.sql` file into your SQL console to create the database schema.
4. You can insert sample data (optional) using additional SQL `INSERT` statements.
5. Run queries to manage appointments, doctors, patients, and records.



---

### Files Included:

* `clinic_db.sql`: The SQL script to create the database and tables.
* `README.md`: This readme file.

---

### License:

This project is open source under the MIT License.
