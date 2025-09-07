
# EMS - Employee Management System 🚀

## Description
This is a React-based Employee Management System (EMS) that allows administrators to create and assign tasks to employees, and employees to view and manage their assigned tasks. It offers distinct dashboards for different roles and manages task lifecycles using local storage.

## Features ✨
- **User Authentication**: Secure login for both administrators and employees. 🔐
- **Role-Based Dashboards**:
  - **Admin Dashboard**: Create tasks, assign them, and monitor employee task statistics. 📊
  - **Employee Dashboard**: View, accept, complete, or fail assigned tasks. ✅
- **Task Management**: Full task lifecycle from creation to completion/failure. 📝
- **Local Storage**: Data persistence for employee and task information. 💾

## Technologies Used 🛠️
- **React**: Frontend UI library. ⚛️
- **Vite**: Fast build tool. ⚡
- **Tailwind CSS**: Utility-first CSS framework. 🎨
- **ESLint**: Code linting. 🧐

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
- **Email**: `admin@me.com`
- **Password**: `123`

Admin can create tasks and monitor employee task statuses.

### Employee Login 👷‍♀️
- **Example Employee**: `employee1@example.com` / `123` (more in `src/utils/localStorage.jsx`)

Employees can manage their assigned tasks (new, accepted, completed, failed).

## Screenshots 📸
Here are some screenshots of the application's UI:
<!-- ![Admin Dashboard](images/admin-dashboard.png) -->
<!-- ![Employee Dashboard](images/employee-dashboard.png) -->

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

## Contributing 🤝
Want to contribute? Here's how:
1. Fork and branch (`feature/your-feature-name`). 🍴🌿
2. Make changes, ensure code style. 🧹
3. Run `npm run lint`. ❌
4. Commit clearly. ✉️
5. Push your branch. ⬆️
6. Open a PR to `main`. 📝

Thank you for your contributions! 🙏
