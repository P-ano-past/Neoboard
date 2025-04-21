# Neoboard - Student & Instructor Management Platform

Neoboard is a platform designed for educational institutions, enabling instructors and students to manage their accounts and automate communication workflows. The app leverages **React.js** for the frontend, **Node.js** and **Express** for the backend, and integrates tools like **AWS SES** for email automation and **Discord** and **Canvas Instructure** for communication.

## 🚀 Key Features:
- **Account Management**: Implemented a comprehensive **RBAC (Role-Based Access Control)** system, allowing for secure account creation, password resets, and account deletions.
- **Frontend Components**: Built reusable UI components, including buttons, dropdowns, and forms using **React Bootstrap** and **Tailwind CSS**.
- **Automated Workflows**: Utilized **AWS SES** for automated password reset emails and **Discord** and **Canvas Instructure** integrations for sending messages to instructors and students.
- **Custom API Routes**: Developed robust backend API routes using **Express** and **Node.js**, ensuring smooth functionality for user management and automation processes.
- **Hosting**: Initially **Dockerized** for local development, but switched to **Railway.app** for deployment due to Docker-related conflicts with their setup.
  
## 🛠️ Tech Stack:
- **Frontend**: React.js, React Bootstrap, Tailwind CSS
- **Backend**: Node.js, Express
- **Authentication & Authorization**: Custom **RBAC** system
- **Email Automation**: AWS SES
- **Communication Integration**: Discord, Canvas Instructure
- **Hosting**: Railway.app (formerly Docker)
  
## 🔧 Development Highlights:
- **Frontend**: Designed and developed reusable, responsive UI components to streamline the user experience. Integrated React Bootstrap and Tailwind CSS for a consistent and modern look.
- **Backend**: Configured secure backend API routes with **Node.js** and **Express**, supporting essential features like account management and RBAC.
- **RBAC System**: Implemented **Role-Based Access Control** (RBAC) from scratch to manage user roles and permissions for instructors, students, and admins.
- **Email Automation**: Integrated **AWS SES** for sending password reset emails and setting up automated workflows for communication between instructors and students.
- **Hosting & Deployment**: Initially set up using **Docker** for local development, but transitioned to **Railway.app** for streamlined deployment, handling conflicts with Docker's procedures.

## 📈 Roadmap:
Future features being considered include:
- Enhanced **user profile** management with a dashboard view for instructors and students.
- **Messaging system** improvements to allow more complex workflows with **Discord** and **Canvas Instructure**.
- **Additional security features** for account management and data encryption.

## 👥 Team:
- **Team Size**: 2 developers
- **My Role**: Lead developer for frontend design, backend API routes, RBAC system, email automation, and integration with external services.

## ⚠️ Project Status:
The project is ongoing, with key features deployed on **Railway.app** and additional functionalities in development. It is currently in active use within the institution for managing student and instructor workflows.

## 📬 Contact:
For more details or collaboration inquiries: [marcsalaver@gmail.com](mailto:marcsalaver@gmail.com)
