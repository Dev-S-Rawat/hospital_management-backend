# 🏥 Hospital Management System (Python)

A **console-based Hospital Management System** written in **Python**.  
This project manages **Admins, Patients, and Doctors**, with features like secure login, patient management, doctor assignments, medicines, reports, and hospital lists.  

---

## ✨ Features

### 🔑 Authentication
- Secure login system with **SHA-256 password hashing**.
- Supports **Admin, Patient, and Doctor** roles.
- Automatic **sign-up option** for new users.

### 👨‍💼 Admin Functions
- View list of hospitals.
- Add/Delete **patients**.
- Add/Delete **doctors**.
- View all user data (patients, doctors, admins).

### 🧑‍🤝‍🧑 Patient Functions
- View assigned **room & bed number**.
- View prescribed **medicines**.
- View uploaded **medical reports**.

### 👨‍⚕️ Doctor Functions
- View patient reports.
- Add medicines for patients.
- Add reports for patients.
- View other patients’ data.

---

## 🛠️ Tech Stack
- **Language:** Python 3  
- **Libraries:** 
  - `hashlib` → for password hashing  
  - `json` → for storing user data  
  - `random` + `string` → for room/bed assignment  
  - `sys` → for program exit  

---
