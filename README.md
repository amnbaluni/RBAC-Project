## VRV Security Frontend Assignment
This repository contains the frontend code for my project, developed as part of the VRV Security assignment for the Frontend Intern position. The project is built using React.js and is centered around designing a user-friendly and responsive Role-Based Access Control (RBAC) interface to manage users, roles, and permissions effectively.

## 🚀 Project Overview
The RBAC UI provides a robust and efficient way for administrators to handle user access and authorization. Its primary goal is to simplify the process of managing user roles and permissions dynamically. Key functionalities include:

Creating, updating, and deleting users.
Assigning and modifying roles and permissions for users.
Real-time search and filtering for efficient user management.
## 🔑 Key Features
📊 Dashboard
Provides an overview of users and their respective roles within the system.
Displays a summary of active/inactive users and assigned roles.
### 👤 Manage Users
Add new users with relevant details like name, email, and status (active/inactive).
Edit user information and update their roles dynamically.
Delete users with proper confirmation to prevent accidental actions.
### 👥 Manage Roles
Define new roles with specific permissions.
Update or delete existing roles.
Handle role-specific functionalities dynamically.
### 🛡️ Manage Permissions
Create, update, or remove permissions for roles.
Ensure dynamic and granular access control by mapping permissions to roles.
### 🔍 Search and Filter
Real-time search functionality for locating users by name or email.
Filter users based on roles, statuses, or other criteria.
## 🛠️ Technologies Used
Frontend Stack
React.js: Building the UI with reusable components.
React Router: Managing navigation between different pages.
Styled-components: Implementing a clean and dynamic CSS-in-JS styling approach.
Context API: Managing global state for theme settings and other global functionality.
Development Tools
npm: Dependency and package management.
VS Code: IDE for writing and debugging code efficiently.
## 🏗️ Getting Started
Follow these steps to set up and run the project on your local environment.

### 1️⃣ Clone the Repository
Clone the project using Git:

             git clone https://github.com/amnbaluni/RBAC-Project

             
### 2️⃣ Navigate to the Project Directory
Go to the frontend directory of the project:

   - cd VRV-Security-Frontend-Assignment/frontend

   - 
### 3️⃣ Install Dependencies
Install all the necessary packages:

    npm install  

    
### 4️⃣ Start the Application
Run the development server:

     npm start  
The application will be available at http://localhost:3000 in your browser.


## 🧪 Testing and Development
Use React DevTools for debugging components and state.
Ensure all user actions like adding, editing, or deleting are thoroughly tested for smooth operation.
Run tests (if available) using Jest or other testing libraries to validate core functionalities.
