# Smart-School-Portal

Smart School Portal is a full-stack School Management System built using **React.js (Frontend)** and **Node.js + Express.js (Backend)**.

It provides a complete role-based platform for managing students, teachers, classes, subjects, attendance, assignments and academic performance.

---

# 📑 Table of Contents

- [🚀 Features](#-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [👥 User Roles](#-user-roles)
- [🏗️ Core Features](#️-core-features)
- [⚛️ React Concepts Implemented](#️-react-concepts-implemented)
- [⚡ Lazy Loading](#-lazy-loading)
- [🗂️ Folder Structure](#️-folder-structure)
- [🛠️ Backend Functionalities](#️-backend-functionalities)
- [📦 Database Design](#-database-design)
- [⚙️ Installation & Setup](#️-installation--setup)
- [🎯 Learning Outcomes](#-learning-outcomes)
- [🌟 Future Enhancements](#-future-enhancements)

---

# 🚀 Features

- Student Dashboard  
- Teacher Dashboard  
- Admin Panel  
- Attendance Monitoring  
- Subject & Faculty Mapping  
- File Upload (Notes & Assignments)  
- Analytics Dashboard  
- Role-Based Authentication  

---

# 🛠️ Tech Stack

## 💻 Frontend
- React.js  
- React Router  
- Context API / Redux Toolkit  
- Axios  
- React Hook Form / Formik  
- Chart.js / Recharts  
- CSS / Tailwind / Bootstrap  

## 🖥️ Backend
- Node.js  
- Express.js  
- MongoDB (Mongoose)  
- JWT Authentication  
- Multer (File Upload)  
- bcrypt (Password Hashing)  

---

# 👥 User Roles

## 🎓 Student
- Login / Logout  
- View Subjects  
- View Assigned Faculty  
- View Attendance %  
- Download Notes  
- View Assignments  
- View Exam Results  
- View Timetable  
- Update Profile  

## 👩‍🏫 Teacher
- Login / Logout  
- View Assigned Classes  
- Mark Attendance  
- Upload Notes (PDF)  
- Create Assignments  
- Add Marks  
- View Student List  
- Update Profile  

## 👨‍💼 Admin
- Manage Classes (1–12)  
- Manage Subjects  
- Add / Edit / Delete Teachers  
- Add / Edit / Delete Students  
- Assign Teacher to Subject  
- Create Timetable  
- View System Analytics  
- Manage Roles  
- Monitor Attendance Reports  

---

# 🏗️ Core Features

## 🔐 Role-Based Authentication
- JWT-based authentication  
- Protected Routes  
- Role-based access control  
- Token validation middleware  
- Password hashing using bcrypt  

## 📅 Attendance Monitoring System
- Teacher marks attendance  
- Attendance stored class-wise and date-wise  
- Student sees attendance %  
- Admin can view reports  
- Attendance analytics chart  

## 📚 Subject & Faculty Mapping
- Class → Subjects  
- Subject → Assigned Teacher  
- Dynamic rendering based on class selection  

## 📂 File Upload System
- Teacher uploads notes & assignments  
- Students download files  
- Files handled using Multer  

## 📊 Analytics Dashboard
- Attendance graph  
- Class strength chart  
- Subject performance  
- Student performance overview  

---

# ⚛️ React Concepts Implemented

## ✅ Functional Components
All components are built using modern functional components.

## ✅ React Hooks
- useState  
- useEffect  
- useContext  
- useRef  
- Custom Hooks  

## ✅ React Router
- Nested routing  
- Dynamic routes  
- Protected routes  
- Role-based route guards  

---

# ⚡ Lazy Loading

To improve performance and reduce bundle size:

- Pages are lazy loaded using `React.lazy()`  
- `Suspense` is used for fallback loading UI  
- Dashboard modules are loaded only when required  

### 🎯 Benefits
- Faster initial load time  
- Optimized performance  
- Scalable architecture  

### Example
- Student module lazy loaded  
- Teacher module lazy loaded  
- Admin module lazy loaded  

---

# 🗂️ Folder Structure

## Frontend

```
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
```

## Backend

```
server/
 ├── controllers/
 ├── models/
 ├── routes/
 ├── middleware/
 ├── config/
 ├── utils/
 └── server.js
```

---

# 🛠️ Backend Functionalities

## 🔐 Authentication APIs
- Register User  
- Login User  
- Generate JWT Token  
- Verify Token Middleware  
- Role-based Authorization  

## 🏫 Class Management
- Create Class  
- Get All Classes  
- Update Class  
- Delete Class  

## 📚 Subject Management
- Add Subject  
- Assign Teacher  
- Get Subjects by Class  
- Update Subject  
- Delete Subject  

## 🎓 Student Management
- Add Student  
- Update Student  
- Delete Student  
- Get Students by Class  
- View Attendance  

## 👩‍🏫 Teacher Management
- Add Teacher  
- Assign Class  
- Update Profile  

## 📅 Attendance APIs
- Mark Attendance  
- Get Attendance by Student  
- Get Attendance by Class  
- Attendance Analytics  

## 📂 File APIs
- Upload Notes  
- Upload Assignments  
- Download Files  
- Delete Files  

---

# 📦 Database Design (MongoDB Collections)

- Users  
- Classes  
- Subjects  
- Attendance  
- Assignments  
- Timetable  
- Marks  
- Notifications  

---

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/smart-school-portal.git
```

---

## 2️⃣ Frontend Setup

```bash
cd client
npm install
npm start
```

---

## 3️⃣ Backend Setup

```bash
cd server
npm install
npm run dev
```

---

## 4️⃣ Environment Variables (Backend)

Create `.env` file inside server folder:

```
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
```

---

# 🎯 Learning Outcomes

Through this project, you will learn:

- Real-world React architecture  
- Role-based authentication system  
- Backend API design using Node.js  
- JWT security implementation  
- File handling  
- Lazy loading optimization  
- State management  
- Reusable component design  
- Performance optimization  

---

# 🌟 Future Enhancements

- Dark / Light Mode  
- Search & Filter  
- Pagination  
- Real-time Notifications (Socket.io)  
- Parent Login  
- Online Quiz System  
- Fee Payment Tracking  
- CI/CD Pipeline  
- Docker Deployment  

---

# 📌 Author

**Reshav Kumar**

---
