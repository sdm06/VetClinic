

# 🐾 Veterinary Clinic Management System

**A comprehensive full-stack solution for managing veterinary appointments, patient records, and medical documentation.**


## 📖 Project Overview

The **Veterinary Clinic Management System** is designed to digitize and streamline the daily workflow of a veterinary practice. By automating appointment scheduling and centralizing patient health records, we enable doctors to focus on care and receptionists to manage operations efficiently.

### 🌟 Key Functionalities

| Feature | Description |
| :--- | :--- |
| **🐕 Patient Records** | Create/Edit animal profiles, medical history, and owner details. |
| **📅 Smart Scheduling** | Book, modify, and cancel appointments. View doctor availability in real-time. |
| **🩺 Medical Docs** | Doctors can securely input diagnosis, treatments, and visit notes. |
| **🔐 Security** | Role-based authentication (RBAC) ensures data privacy for Admins, Doctors, and Receptionists. |
| **📊 Admin Dashboard** | Manage system settings, user roles, and ensure data integrity. |

---

## 👥 Team & Roles

| Name | Role | Responsibilities |
| :--- | :--- | :--- |
| **Stepan Turani** | Project Manager / Backend | Project coordination, server-side logic, final presentation. |
| **Sviatoslav Diachuk** | Database / Full Stack | DB structure & security, UI implementation, API integration. |
| **Volha Silmanovich** | UI/UX Designer / Tester | Figma design, wireframing, QA testing, bug documentation. |

---

## ⚙️ Tech Stack

* **Frontend:** React.js
* **Backend:** Node.js, Express
* **Database:** Prisma ORM (with PostgreSQL/MySQL)
* **Design:** Figma

---

## 🚀 Getting Started

Follow these instructions to set up the project locally.

### Prerequisites
* Node.js & npm installed
* Git installed
* Database URL ready

### Installation Guide

**1. Clone the repository**
```bash
git clone [https://github.com/Kishouu/VetClinic.git](https://github.com/Kishouu/VetClinic.git)

```

**2. Install Frontend Dependencies**
Navigate to the root directory:

```bash
npm install

```

**3. Install Backend Dependencies**
Navigate to the server directory:

```bash
cd server
npm install

```

**4. Database Setup**
While still in the `/server` directory:

```bash
# Generate Prisma Client
npx prisma generate

# Push schema to your database
npx prisma db push

# Seed the database with initial data
node prisma/seed.js

```

### 🏃‍♂️ Running the Application

You will need to open **3 separate terminal** windows.

**Terminal 1: Backend Server**

```bash
cd server
node index.js

```

**Terminal 2: Database Studio (Optional)**

```bash
cd server
npx prisma studio

```

**Terminal 3: Client (Frontend)**
Return to the root directory:

```bash
npm start

```

**5. Access the App**
Open your browser and navigate to:
`http://localhost:3000/`

---

## 🏗️ System Structure & User Journey

1. **Home Page:** Services overview & Login.
2. **Login:** Secure authentication routing users to specific dashboards.
3. **Dashboards:**
* *Doctor:* View schedule, access medical docs.
* *Receptionist:* Calendar view, booking system.
* *Admin:* User management panel.



---

```
