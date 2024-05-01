# **Health Care Server**

Welcome to the **HealthCare server-side** documentation! This document provides an overview of the server-side application components, architecture, and functionalities to guide you through the project's backend.

## Technologies

- **NodeJS:** Used for server-side application development.
- **Express:** A minimal and flexible Node.js web application framework used to build APIs and manage routes.
- **Prisma:** ORM (Object-Relational Mapping) tool for efficient interaction with the PostgreSQL database.
- **PostgreSQL:** Relational database management system for secure and scalable data management.

## Features

### Admin Functionalities

- **Account Management:** Create and manage doctor accounts.
- **Appointment Management:** Create schedule slots and manage doctor appointment slots (e.g., change status of appointments).
- **Access to Information:** View appointment history and details, access and manage doctor profiles, and view metadata.

### Doctor Functionalities

- **Appointment Management:** View upcoming appointments, set appointment slots, and take appointments.
- **Patient Profile Management:** Access patient profiles and medical history, view diagnostic test reports, and view previous prescriptions (if any).
- **Prescription Management:** Generate prescriptions for patients during and after consultations and send them through email.

### Patient Functionalities

- **Account Management:** Register a new account, recover passwords, and maintain account security.
- **Appointment Booking:** Schedule appointments, book with specific doctors, and manage appointments.
- **Medical Record Management:** Manage personal profile data and medical history, and upload diagnostic test reports.
- **Prescription Access:** Access and view prescriptions and receive them through the platform and email.
- **Payment and Confirmation:** Pay consultation fees when booking appointments, receive email confirmations and invoices, and handle automatic booking cancellations.
- **Reviews:** Provide reviews and ratings for consulting doctors and manage previous reviews.

### Security and Communication

- **Authentication and Authorization:** Implement secure authentication and authorization mechanisms.
- **Real-time Communication:** Use Agora.io for real-time video and audio communication during consultations.

## **Getting Started**

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/sifat-ur-rahman/HealthCare-Server.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd HealthCare-Server
   ```

3. Please update the filename from `.env.example` to `.env`
4. **Install Dependencies:**

   ```bash
   npm install
   ```

5. **Start the Server:**

   ```bash
   npm run dev
   ```

   The server will be running at **`http://localhost:5000`** .

#### Postman API Documentation: https://documenter.getpostman.com/view/26694209/2s9YynmjXH
