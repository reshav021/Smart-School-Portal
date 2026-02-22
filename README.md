# Smart-School-Portal
Smart School Portal is a full-stack school management system built using React.js (Frontend) and Node.js + Express.js (Backend).

It provides a complete role-based platform for managing students, teachers, classes, subjects, attendance, assignments, and academic performance.

The system includes:

Student Dashboard

Teacher Dashboard

Admin Panel

Attendance Monitoring

Subject & Faculty Mapping

File Upload (Notes & Assignments)

Analytics Dashboard

Role-Based Authentication

This project is designed to simulate a real-world school ERP system and demonstrate modern frontend and backend architecture.

🚀 Tech Stack
Frontend

React.js

React Router

Context API / Redux Toolkit

Axios

React Hook Form / Formik

Chart.js / Recharts

CSS / Tailwind / Bootstrap

Backend

Node.js

Express.js

MongoDB (Mongoose)

JWT Authentication

Multer (File Upload)

bcrypt (Password Hashing)

👥 User Roles
🎓 Student

Login / Logout

View Subjects

View Assigned Faculty

View Attendance %

Download Notes

View Assignments

View Exam Results

View Timetable

Update Profile

👩‍🏫 Teacher

Login / Logout

View Assigned Classes

Mark Attendance

Upload Notes (PDF)

Create Assignments

Add Marks

View Student List

Update Profile

👨‍💼 Admin

Manage Classes (1–12)

Manage Subjects

Add / Edit / Delete Teachers

Add / Edit / Delete Students

Assign Teacher to Subject

Create Timetable

View System Analytics

Manage Roles

Monitor Attendance Reports

🏗️ Core Features
1️⃣ Role-Based Authentication

JWT based authentication

Protected Routes

Role-based access control

Token validation middleware

Password hashing using bcrypt

2️⃣ Attendance Monitoring System

Teacher marks attendance

Attendance stored class-wise and date-wise

Student sees attendance %

Admin can view reports

Attendance analytics chart

3️⃣ Subject & Faculty Mapping

Class → Subjects

Subject → Assigned Teacher

Dynamic rendering based on class selection

4️⃣ Dashboard System

Each user has:

Sidebar navigation

Role-based menu items

Dynamic content rendering

5️⃣ File Upload System

Teacher uploads:

Notes (PDF)

Assignments

Student downloads files

Files stored using Multer

6️⃣ Timetable Management

Admin creates timetable

Class-based timetable view

Student & Teacher access

7️⃣ Analytics Dashboard

Attendance graph

Class strength chart

Subject performance

Student performance overview

⚛️ React Concepts Implemented
✅ Functional Components

All components built using modern functional components.

✅ React Hooks

useState

useEffect

useContext

useRef

Custom Hooks

✅ React Router

Nested routing

Dynamic routes

Protected routes

Role-based route guards

⚡ Lazy Loading Implementation

To improve performance and reduce bundle size:

Pages are lazy loaded using React.lazy()

Suspense is used for fallback loading UI

Dashboard modules are loaded only when required

Benefits:

Faster initial load time

Optimized performance

Scalable architecture

Example structure:

Student module lazy loaded

Teacher module lazy loaded

Admin module lazy loaded

🗂️ Folder Structure (Frontend)
src/
 ├── components/
 ├── pages/
 ├── layouts/
 ├── routes/
 ├── context/ or store/
 ├── hooks/
 ├── services/
 ├── utils/
 ├── assets/
🛠️ Backend Functionalities (Node.js)
🔐 Authentication & Authorization

Register user (Student / Teacher)

Login user

Generate JWT token

Middleware for token verification

Role-based middleware

🏫 Class Management APIs

Create Class

Get All Classes

Update Class

Delete Class

📚 Subject Management APIs

Add Subject to Class

Get Subjects by Class

Assign Teacher to Subject

Update Subject

Delete Subject

👩‍🏫 Teacher APIs

Add Teacher

Get Teacher Details

Assign Class

Update Profile

🎓 Student APIs

Add Student

Get Students by Class

Update Student

Delete Student

View Attendance

📅 Attendance APIs

Mark Attendance

Get Attendance by Student

Get Attendance by Class

Attendance Analytics

📂 File Upload APIs

Upload Notes

Upload Assignment

Download Files

Delete Files

📊 Analytics APIs

Class strength count

Attendance percentage

Subject-wise performance

🧠 Advanced Features (Optional Improvements)

Dark / Light Mode

Search & Filter

Pagination

Real-time Notifications (Socket.io)

Leave Request System

Online Quiz System

Parent Login

Fee Payment Tracking

Profile Image Upload

📦 Database Design (MongoDB Collections)

Users

Classes

Subjects

Attendance

Assignments

Timetable

Marks

Notifications

🎯 Learning Outcomes

Through this project, you will learn:

Real-world React architecture

Role-based authentication system

Backend API design using Node.js

JWT security implementation

File handling

Lazy loading optimization

State management

Reusable component design

Performance optimization

🌟 Future Enhancements

Deploy using:

Frontend → Vercel / Netlify

Backend → Render / Railway

Add CI/CD pipeline

Dockerize application
