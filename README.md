# 💼 Job Portal Application

A full-stack **Job Portal Application** built with the **MERN stack (MongoDB, Express.js, React.js, Node.js)** that enables users to register, login, post jobs, search listings, and apply for opportunities — all in a secure and responsive environment.

---

## 🚀 Features

- 🔐 **JWT-based Authentication** (login/signup with role-based access)
- 👤 **User Roles**: Admin, Recruiter, Applicant
- 📝 **Job Posting**: Recruiters can create, edit, and delete job listings
- 🔍 **Job Search**: Filter jobs by keyword, company, and location
- 📑 **Job Applications**: Applicants can apply and track their applications
- 🧾 **Pagination & Real-Time Validation**
- 💻 **Responsive UI**: Built with React and styled-components
- 🔗 **Frontend-Backend Integration** via RESTful APIs

---

## 🛠 Tech Stack

| Layer        | Technology                     |
|--------------|--------------------------------|
| Frontend     | React.js, styled-components    |
| Backend      | Node.js, Express.js            |
| Database     | MongoDB (with Mongoose)        |
| Authentication | JWT, bcrypt                   |
| API Testing  | Postman                        |
| Tools        | Git, Visual Studio Code        |

---

## 📦 Installation

### 🔧 Prerequisites

- Node.js and npm
- MongoDB (local or Atlas)
- Git

### 💻 Setup Instructions

```bash
# Clone the repository
git clone https://github.com/your-username/job-portal-app.git
cd job-portal-app

# Backend setup
cd backend
npm install
npm run dev

# Frontend setup (in a new terminal)
cd frontend
npm install
npm start
