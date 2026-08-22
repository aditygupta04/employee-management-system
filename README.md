# Employee Task Management System

A role-based task management application built with **React**, using the **Context API** for state management. The app provides separate dashboards for Admins and Employees to create, assign, and track tasks through their lifecycle.

## Features

- **Role-based dashboards** — separate views and permissions for Admin and Employee users
- **Task lifecycle tracking** — tasks move through New → Active → Completed / Failed states
- **Admin task assignment** — create tasks with category, due date, and assign them to specific employees
- **Per-employee task summaries** — quick overview of task counts and status for each employee
- **Responsive UI** — built with Tailwind CSS for a clean, dark-themed interface across devices

## Tech Stack

- React.js
- Context API (state management)
- Tailwind CSS
- Vite

## Note

This is a frontend-focused project — authentication and data persistence are simulated using the Context API and browser localStorage rather than a backend/database. It was built primarily to demonstrate component architecture, state management patterns, and role-based UI logic in React.

## Getting Started

\`\`\`bash
git clone <your-repo-url>
cd ems
npm install
npm run dev
\`\`\`
