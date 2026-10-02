# EventForce-Management-System
Salesforce-based Event Management System for managing events, clients, vendors, venues, feedback, approvals, and automation.
# EventForce Management System

An end-to-end Event Management Platform designed to streamline event creation, venue booking, registration tracking, and resource management. Built as a Networking & Web Application (NM) project, **EventForce** simplifies event operations for organizers, vendors, and attendees.

---

## 🚀 Features

- **User Authentication & Roles:** Secure sign-up/login system supporting multiple user roles (Admins, Event Organizers, and Attendees).
- **Event Dashboard:** Create, update, view, and manage events in real time.
- **Ticket & Registration System:** Attendees can register for events, view ticket availability, and manage registrations.
- **Venue & Resource Allocation:** Track venue availability, capacities, and event schedules.
- **Analytics & Reporting:** Quick overview of total attendees, event status, and performance metrics.

---

## 🛠️ Tech Stack

> *Customize this section based on the exact technologies you used for your NM project.*

- **Frontend:** React / HTML5, CSS3, JavaScript (Bootstrap / Tailwind CSS)
- **Backend:** Node.js (Express.js) / Python (Django / Flask)
- **Database:** PostgreSQL / MySQL / MongoDB
- **Authentication:** JWT (JSON Web Tokens) / Session-based authentication

---

## 📋 Prerequisites

Before running this project locally, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v16.x or higher)
- [Git](https://git-scm.com/)
- Database server (e.g., MongoDB / MySQL / PostgreSQL)

---

## ⚙️ Installation & Setup

1. **Clone the Repository**
   ```bash
   git clone [https://github.com/your-username/eventforce-management-system.git](https://github.com/your-username/eventforce-management-system.git)
   cd eventforce-management-system
   cd backend
npm install
cd ../frontend
npm install
PORT=5000
DATABASE_URL=your_database_connection_string
JWT_SECRET=your_jwt_secret_key
