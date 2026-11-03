# EMS – Employee Task Management System

A responsive Employee Management System built with **React.js, Vite, and Tailwind CSS**. The application provides separate Admin and Employee dashboards to manage tasks, monitor progress, and organize employee workflows through an interactive interface.

## Overview

EMS is a frontend-based employee task management application designed to simplify task allocation and progress tracking.

Administrators can create and assign tasks to employees, while employees can view assigned tasks and update their status. The application uses browser localStorage to persist demo users, tasks, and application state.

## Key Features

### Admin Dashboard
- Create and assign tasks to employees.
- View employee task statistics.
- Monitor new, accepted, completed, and failed tasks.
- Manage task allocation through an interactive dashboard.

### Employee Dashboard
- View assigned tasks.
- Accept newly assigned tasks.
- Mark tasks as completed or failed.
- Track task progress through categorized task cards.
- View task statistics and status updates.

### Application Features
- Role-based Admin and Employee dashboards.
- Component-based React architecture.
- Persistent demo data using browser localStorage.
- Responsive user interface.
- Dynamic task status updates.
- Reusable UI components.

## Tech Stack

| Technology | Purpose |
|---|---|
| React.js | Component-based UI development |
| JavaScript (ES6+) | Application logic |
| Vite | Development server and build tooling |
| Tailwind CSS | Utility-first styling |
| CSS3 | Custom styling |
| localStorage | Browser-based data persistence |
| ESLint | Code quality and linting |

## Application Architecture

```text
EMS/
│
├── public/
│
├── src/
│   ├── assets/
│   │
│   ├── components/
│   │   ├── Auth/
│   │   │   └── Login.jsx
│   │   │
│   │   ├── Dashboard/
│   │   │   ├── AdminDashboard.jsx
│   │   │   └── EmployeeDashboard.jsx
│   │   │
│   │   ├── TaskList/
│   │   │   ├── AcceptTask.jsx
│   │   │   ├── CompleteTask.jsx
│   │   │   ├── FailedTask.jsx
│   │   │   ├── NewTask.jsx
│   │   │   └── TaskList.jsx
│   │   │
│   │   └── other/
│   │       ├── AllTask.jsx
│   │       ├── CreateTask.jsx
│   │       ├── Header.jsx
│   │       └── TaskListNumbers.jsx
│   │
│   ├── context/
│   │   └── AuthProvider.jsx
│   │
│   ├── utils/
│   │   └── localStorage.jsx
│   │
│   ├── App.jsx
│   ├── App.css
│   ├── index.css
│   └── main.jsx
│
├── .gitignore
├── package.json
├── package-lock.json
├── tailwind.config.js
└── vite.config.js
```

## Getting Started

Follow these steps to run the project locally.

### 1. Clone the repository

```bash
git clone https://github.com/aman07052005/EMS-Employee-Task-Management-System-.git
```

### 2. Navigate to the project directory

```bash
cd EMS-Employee-Task-Management-System-
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the development server

```bash
npm run dev
```

Open the local URL displayed in your terminal to access the application.

## Demo Login Credentials

The project includes predefined demo accounts for testing the Admin and Employee dashboards.

| Role | Email | Password |
|---|---|---|
| Admin | admin@me.com | 123 |
| Employee | e@e.com | 123 |

**Note:** These are demonstration credentials for the frontend application, not production-secure authentication.

## Task Management Workflow

1. The administrator logs into the Admin Dashboard.
2. The administrator creates a task with relevant details.
3. The task is assigned to an employee.
4. The employee logs into their dashboard.
5. The employee accepts and works on the assigned task.
6. The employee updates the task status to completed or failed.
7. The dashboard reflects the updated task information.

## Technical Implementation

- **Component Reusability:** The interface is divided into reusable components for dashboards, authentication, task cards, and task statistics.
- **Context API:** React Context is used to manage and share authentication-related application state.
- **State Management:** React state drives dashboard rendering and task status updates.
- **Data Persistence:** Browser localStorage is used to retain demo application data across page refreshes.
- **Task Categorization:** Tasks are organized according to their current status, making progress easier to monitor.

## Current Scope and Future Improvements

The current version demonstrates frontend task management workflows using localStorage.

Potential future enhancements include:

- Backend integration using Node.js and Express.js.
- Database integration with MongoDB or PostgreSQL.
- Secure authentication using JWT and password hashing.
- Role-based authorization on the server.
- Employee profile management.
- Real-time task notifications.
- Deployment with a production backend.

## Project Information

**Project:** Employee Task Management System  
**Category:** Frontend Web Application  
**Developer:** Aman Yadav  
**GitHub:** [aman07052005](https://github.com/aman07052005)

---

If you find this project useful, consider giving the repository a ⭐ on GitHub.

