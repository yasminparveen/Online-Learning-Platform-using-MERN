# Online Learning Platform Using MERN

## Project Overview
The **Online Learning Platform (OLP)** is a dynamic web-based educational solution developed using the MERN stack (MongoDB, Express.js, React.js, Node.js). The platform is designed to provide an accessible and structured environment for students, educators, and administrators. It supports diverse user roles and enables:
- **Students** to enroll in courses, track progress, and earn certificates.
- **Teachers** to create and manage course content.
- **Administrators** to oversee platform activity and maintain security.

The platform combines a responsive UI with a scalable backend to deliver an efficient and interactive learning experience.

---

## Features

### Students
- Register, explore, and enroll in courses.
- Access course materials, including video lectures and assignments.
- Track progress and resume courses from where they left off.
- Participate in discussions and live webinars.
- Earn and download certificates upon course completion.
- Enroll in free or paid courses using a secure payment system.

### Teachers
- Create, update, and manage course content.
- Add sections to courses.
- Monitor course enrollments and interact with students.

### Administrators
- Monitor platform activity and user interactions.
- Manage course listings and enrolled students.
- Ensure a secure and seamless user experience.

---

## Technical Architecture
The project follows a **client-server model**:
- **Frontend:** Built using React.js, with Bootstrap and Material UI for enhanced UI/UX. Axios is used for API integration.
- **Backend:** Developed with Node.js and Express.js to handle server-side logic and API routing.
- **Database:** MongoDB serves as the data storage solution for user, course, and enrollment data.

---

## Prerequisites

### Tools and Libraries
1. **Vite**: For optimized frontend development.
   - Installation: `npm create vite@latest`
2. **Node.js**: JavaScript runtime for the backend.
   - [Download Node.js](https://nodejs.org/en/download/)
3. **Express.js**: Framework for server-side routing and middleware.
   - Installation: `npm install express`
4. **MongoDB**: NoSQL database for data storage.
   - [Download MongoDB](https://www.mongodb.com/try/download/community)
5. **React.js**: Library for creating interactive user interfaces.
   - [React.js Installation Guide](https://reactjs.org/docs/create-a-new-react-app.html)
6. Other Dependencies:
   - `cors`, `bcryptjs`, `dotenv`, `mongoose`, `multer`, `jsonwebtoken`, `nodemon` (backend).
   - `axios`, `antd`, `mdb-react-ui-kit`, `react-bootstrap` (frontend).

---

## Installation and Setup

### Backend
1. Navigate to the `backend` folder.
2. Install dependencies:

    ```bash
    npm install
    ```
3. Start the `backend` server: 

    ```bash
    npm start
    ```  
### Frontend
1. Navigate to the `frontend` folder.
2. Install dependencies:

    ```bash
    npm install
    ```
3. Start the `frontend` server:

    ```bash
    npm start
    ```  