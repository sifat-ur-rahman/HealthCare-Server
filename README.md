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
   git clone https://github.com/Programming-Hero-Next-Level-Development/health-care-server.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd health-care-server
   ```

3. Please update the filename from `.env.example` to `.env`
4. **Install Dependencies:**

   ```bash
   yarn install
   ```

5. **Start the Server:**

   ```bash
   yarn dev
   ```

   The server will be running at **`http://localhost:3000`** .

## **Contributing Guidelines**

To contribute to the project, follow these guidelines:

1.  **Create a Feature Branch:**
    Before starting work on a new feature, create a feature branch:
    `bash
git checkout -b feature/your-feature-name
`
2.  **Write Code:**
    Implement the feature or fix the bug on your feature branch.
3.  **Commit Changes:**
    Commit your changes with a meaningful commit message:
    `bash
git commit -m "Add your commit message here"
`
4.  **Push Changes:**
    Push your changes to your feature branch:
    `bash
git push origin feature/your-feature-name
`
5.  **Create a Pull Request (PR):**
    Create a pull request from your feature branch to the **`development`** branch on GitHub. Ensure the PR title and description are descriptive.
6.  **Code Review:**
    Your code will be reviewed by other team members. Address any feedback and make necessary changes.

## **Additional Notes**

- **Main Branch:**
  The **`main`** branch is reserved for stable releases. Do not directly push to the main branch.
- **Issues and Bug Tracking:**
  Use the GitHub Issues tab to report bugs, suggest features, or discuss enhancements.
- **Coding Standards:**
  Follow the coding standards and conventions established by the team. Ensure your code is well-documented.

#### Postman API Documentation: https://documenter.getpostman.com/view/26694209/2s9YynmjXH
