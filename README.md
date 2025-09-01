
# 🏥 Hospital Management System (Java Console Application)

A simple **console-based Hospital Management System** built in **Java** using **Object-Oriented Programming (OOP) principles**.
This project allows hospitals to manage **Patients, Doctors, and Appointments** with unique ID tracking, input validation, and a menu-driven interface.

---

## ✨ Features

* ➕ **Add Patient** – Register a new patient with name, age, and gender.
* ➕ **Add Doctor** – Register a new doctor with name and specialty.
* 📅 **Schedule Appointment** – Book an appointment between a patient and a doctor with a given date.
* 👥 **View Patients** – Display all registered patients with unique IDs.
* 🩺 **View Doctors** – Display all registered doctors with unique IDs.
* 📖 **View Appointments** – Display all scheduled appointments with patient and doctor details.
* 🔐 **Input Validation** – Ensures smooth interaction and prevents invalid entries.
* ⚡ **Unique ID Tracking** – Each patient and doctor is assigned a unique ID automatically.

---

## 🛠️ Technologies Used

* **Language:** Java
* **Paradigm:** Object-Oriented Programming (Encapsulation, Class Interaction)
* **Data Structures:** Java Collections Framework (ArrayList)
* **Tools:** Java Compiler (JDK), Terminal/Command Prompt

---

## 📂 Project Structure

```
HospitalManagementSystem/
│
├── HospitalManagement.java   # Main driver class with menu system
├── Patient.java              # Patient class with ID, name, age, gender
├── Doctor.java               # Doctor class with ID, name, specialty
├── Appointment.java          # Appointment class linking patient, doctor, and date
└── README.md                 # Documentation
```

---

## ▶️ How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/Hospital-Management-System.git
   ```

2. Navigate to the project folder:

   ```bash
   cd Hospital-Management-System
   ```

3. Compile the Java files:

   ```bash
   javac HospitalManagement.java Patient.java Doctor.java Appointment.java
   ```

4. Run the program:

   ```bash
   java HospitalManagement
   ```

---

## 📌 Sample Menu

```
Hospital Management System
1. Add Patient
2. Add Doctor
3. Schedule Appointment
4. View Patients
5. View Doctors
6. View Appointments
0. Exit
Enter your choice:
```

---

## 📖 Example Flow

* Add a patient:

  ```
  Enter Patient Name: John
  Enter Patient Age: 30
  Enter Patient Gender: Male
  Patient added successfully!
  ```

* Add a doctor:

  ```
  Enter Doctor Name: Dr. Smith
  Enter Doctor Specialty: Cardiology
  Doctor added successfully!
  ```

* Schedule an appointment:

  ```
  Enter Patient ID: 1
  Enter Doctor ID: 1
  Enter Appointment Date (YYYY-MM-DD): 2025-09-10
  Appointment scheduled successfully!
  ```

---

## 🚀 Future Enhancements

* Store data in files or a database (instead of runtime only).
* Implement search functionality for patients/doctors.
* Add update and delete options for records.
* Build a GUI version using JavaFX or Swing.

---


