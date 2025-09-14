# EMS - Employee Management System 🚀

A simple **Employee Management System** built with **React** as a practice project to sharpen React development skills.  
The app fetches employee and task data from a **JSON file** and displays it in the frontend with role-based dashboards for **Admins** and **Users**.  

---

## 🚀 Features
- 🔐 **Role-based Login** – Admin and User have separate sign-in options.  
- 📊 **User Dashboard** – View assigned tasks and check completion status.  
- 🛠️ **Admin Dashboard** – Monitor employees and track task completion.  
- 🔄 **Sign-in / Sign-out** – Authentication flow for secure session handling.  
- 🌐 **Context API** – Smooth global state management and data passing.  
- 🎨 **TailwindCSS Styling** – Responsive and modern UI design.  

  

---

## 🧩 Tech Stack & Libraries Used
- ⚛️ **React** – For building the frontend with reusable UI components.  
- 🎨 **TailwindCSS** – Utility-first CSS framework for responsive styling.  
- 🔗 **Context API** – For global state management and avoiding prop drilling.  
- 📂 **JSON File** – Used as a mock data source to simulate backend functionality.  

---

## Project Structure 📁
```
ems/
├── src/
│   ├── App.jsx
│   ├── main.jsx
│   ├── components/
│   │   ├── Auth/
│   │   │   └── Login.jsx
│   │   ├── Dashboard/
│   │   │   ├── AdminDashboard.jsx
│   │   │   └── EmployeeDashboard.jsx
│   │   ├── other/
│   │   │   ├── CreateTask.jsx
│   │   │   └── Header.jsx
│   │   └── TaskList/
│   │       └── TaskList.jsx
│   ├── context/
│   │   └── AuthProvider.jsx
│   └── utils/
│       └── localStorage.jsx
├── package.json
├── tailwind.config.js
└── vite.config.js
```
---

## Setup and Installation 💻
To get started, clone the repository and install dependencies:

```bash
git clone <repository-url>
cd ems
npm install
# or yarn install
```

Run the development server:
```bash
npm run dev
# or yarn dev
```
The application will be available at `http://localhost:port/`.

## Usage 📖

### Admin Login 🧑‍💻
- **Email**: `admin@example.com`
- **Password**: `123`

Admin can create tasks and monitor employee task statuses.

### Employee Login 👷‍♀️
- **Example Employee**: `employee1@example.com` / `123` (more in `src/utils/localStorage.jsx`)
---
