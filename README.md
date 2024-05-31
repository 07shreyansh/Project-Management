# Project Management Web Application

## Overview

This project management web application is built using the MERN stack (MongoDB, Express.js, React.js, Node.js) and designed with Ant Design (AntD) and Tailwind CSS. The application uses JSON Web Tokens (JWT) for authentication and supports three types of user profiles: owner, admin, and employee. Owners and admins can assign tasks to employees.

## Features

- **User Authentication**: Secure login and registration using JWT.
- **User Roles**: Three types of user profiles - Owner, Admin, and Employee.
- **Task Management**: Owners and Admins can assign tasks to Employees.
- **Responsive Design**: Designed with Ant Design (AntD) and Tailwind CSS for a responsive and modern user interface.

## Tech Stack

- **Frontend**: React.js, Ant Design (AntD), Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)

## Installation

### Prerequisites

- Node.js
- MongoDB

### Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/project-management-web-app.git
   cd project-management-web-app
   
2. **Install node modules:**

   ```bash
   npm i

## Project Structure

```plaintext
    project-management-web-app/
├── client/                     # Frontend application (React.js)
│   ├── public/
│   └── src/
├── server/                     # Backend application (Node.js, Express.js)
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── server.js
├── .gitignore
├── README.md
└── package.json
```

