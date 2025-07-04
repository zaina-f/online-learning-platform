# 🎓 Online Learning Platform

A full-stack online education platform developed as part of an internship.  
It allows instructors to manage courses and students to enroll, track progress, and engage in discussions.

---

## ✨ Features

- 👩‍🏫 Instructor Dashboard
  - Create, edit, and delete courses
  - Upload lessons with video links
  - View enrolled students

- 👨‍🎓 Learner Experience
  - Register/login
  - Enroll in courses
  - Track lesson progress
  - Access course discussions

- 🗣️ Discussion Channel
  - Post and reply to course-specific questions

- 📊 Progress Tracking
  - Per-course lesson tracking for each user

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript (static pages)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Other Tools**: MongoDB Compass, Postman, VS Code

---

## 📁 Folder Structure

```plaintext
├── frontend/
│   ├── createcourse.html
│   ├── dashboard.html
│   ├── discussion.html
│   ├── editcourse.html
│   ├── index.html
│   ├── instructor.html
│   ├── login.html
│   ├── mycourses.html
│   ├── register.html
│   ├── style.css
│   └── viewcourse.html

├── models/
│   ├── Course.js
│   ├── Discussions.js
│   ├── Enrollment.js
│   ├── Progress.js
│   └── User.js

├── routes/
│   ├── auth.js
│   ├── courses.js
│   ├── discussions.js
│   ├── enrollments.js
│   └── progress.js

├── .env
├── package.json
├── package-lock.json
├── server.js
