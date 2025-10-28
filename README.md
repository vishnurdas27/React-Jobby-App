# 💼 React Jobby App

The **Jobby App** is a dynamic React-based job portal that allows users to explore, search, and apply for jobs seamlessly.  
It includes user authentication, protected routes, API integration, and advanced filtering — built to simulate a real-world job search experience.

---
<a>https://jobby55.ccbp.tech/</a>
---

## 🚀 Features

### 🔐 Authentication
- Login system with JWT token authentication.
- Displays error message for invalid credentials.
- Redirects users to the **Home** page on successful login.
- Unauthenticated users are redirected to the **Login** page when accessing protected routes.
- Authenticated users are redirected to **Home** when visiting the Login page again.

### 🏠 Home Page
- Displays an introduction to the platform.
- Clicking the **Find Jobs** button navigates to the **Jobs** page.

### 💼 Jobs Page
- Fetches user profile and available jobs using API calls.
- Displays a **Loader** while data is being fetched.
- Shows **Failure View** if API requests fail, with a **Retry** option.
- Users can filter jobs by:
  - **Employment Type** (Full-time, Part-time, etc.)
  - **Salary Range**
  - **Search Input**
- Displays **No Jobs View** when no results match the filters.
- Clicking on a job navigates to its **Job Details** page.

### 📋 Job Details Page
- Displays detailed information about the selected job.
- Shows similar job recommendations.
- **Visit** button opens the company website in a new tab.
- Loader and Failure View included with Retry functionality.

### 🚫 Not Found Page
- When an invalid route is entered, users are shown a **Not Found** view.

### 🧭 Header
- Clicking the **Logo** navigates to the Home page.
- Navigation links for Home and Jobs.
- **Logout** button clears the token and redirects to Login.

---

## 🧱 Tech Stack

- **React.js**
- **React Router DOM**
- **JavaScript (ES6+)**
- **CSS / TailwindCSS**
- **js-cookie** — for JWT management  
- **react-loader-spinner** — for loading animations
- **REST APIs** (from [CCBP APIs](https://apis.ccbp.in))

---

## 🔗 Login Creds
  -{ "username": "rahul", "password": "rahul@2021" }
