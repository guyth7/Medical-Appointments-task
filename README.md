#  Full-Stack Medical Complex Management System

A comprehensive web application designed to streamline healthcare and clinic operations within a medical complex. Built with a robust **Laravel RESTful API** backend and a dynamic **React.js** frontend.

---

##  Key Features

###  Medical & Operational Management
- **Appointment Scheduling:** Book, reschedule, and track patient appointments with real-time doctor availability checks.
- **Electronic Medical Records (EMR):** Manage doctor working hours, prescriptions, and medical records.
- **Clinic Management:** Multi-specialty clinic setup, doctor shift scheduling, and service configurations.
- **Role-Based Access Control (RBAC):** Secure access permissions tailored for Admins, Doctors, and Patients.

###  Technical Highlights
- Modern **Full-Stack Architecture** with clear separation between Backend and Frontend.
- Structured JSON REST API responses with form request validations.
- Responsive and user-friendly user interface and dashboard.

---

##  Tech Stack

- **Backend:** Laravel (PHP)
- **Frontend:** React.js
- **Database:** MySQL
- **Authentication:** Laravel Sanctum / JWT
- **API Protocol:** RESTful API

---

##  Repository Structure

```text
fullStack-medical-complex/
├── backend/          # Laravel RESTful API Source Code
└── frontend/         # React.js Frontend Application
```
## 1. Backend Setup (Laravel)
```text
cd backend
```
```
composer install
```
```
cp .env.example .env
```
```
php artisan key:generate
```
# Configure your MySQL database credentials in the .env file

```
php artisan migrate --seed
```
```
php artisan serve
```
## 2. Frontend Setup (React)
```text
cd frontend
```
```
npm install
```
```
npm start
