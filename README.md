````markdown
# Task Manager

A full-stack **Task Manager Application** built using **React, TailwindCSS, Node.js, Express.js, and MongoDB**.  
This app provides secure user authentication and a clean UI for managing tasks effectively.

---

## Table of Contents

- [Features](#features)
- [Tools and Technologies](#tools-and-technologies)
- [Dependencies](#dependencies)
- [Dev-dependencies](#dev-dependencies)
- [Prerequisites](#prerequisites)
- [Installation and setup](#installation-and-setup)
- [Backend API](#backend-api)
- [Frontend pages](#frontend-pages)
- [npm scripts](#npm-scripts)
- [Useful Links](#useful-links)

---

## Features

### User-side features
- Signup  
- Login  
- Logout  
- Add tasks  
- View tasks  
- Update tasks  
- Delete tasks  

### Developer-side features
- Toasts for success & error messages  
- Form validations (frontend & backend)  
- Fully responsive Navbar  
- Token-based authentication with JWT  
- 404 page for wrong URLs  
- Global user state using Redux  
- Custom loaders  
- Layout components for reusable UI  
- Theme-based colors (Tailwind)  
- Tooltips for better UX  
- Dynamic document titles  
- Redirect to previous page after login  
- Routes protection (frontend + middleware)  
- Proper HTTP status codes in backend  
- Clean folder structure & best practices  

---

## Tools and Technologies
- **Frontend:** HTML, CSS, JavaScript, React, Redux, Tailwind CSS  
- **Backend:** Node.js, Express.js, MongoDB  
- **Other:** JWT for authentication, REST APIs  

---

## Dependencies
Major dependencies used:
- axios  
- react, react-dom  
- react-redux, redux, redux-thunk  
- react-router-dom  
- react-toastify  
- bcrypt  
- cors  
- dotenv  
- express  
- jsonwebtoken  
- mongoose  

---

## Dev-dependencies
- nodemon  
- concurrently  

---

## Prerequisites
- Node.js installed on system  
- MongoDB database (local/Atlas)  
- Code editor (VS Code recommended)  

---

## Installation and Setup

1. Clone the repo
   ```sh
   git clone https://github.com/VenkataSubramanyamKamboji/task-manager.git
   cd task-manager
````

2. Install dependencies

   ```sh
   npm run install-all
   ```

3. Create a `.env` file in the backend folder and add:

   ```env
   MONGO_URI=your-mongodb-uri
   JWT_SECRET=your-secret-key
   PORT=5000
   ```

4. Run the app

   ```sh
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000)

---

## Backend API

<pre>
POST     /api/auth/signup
POST     /api/auth/login
GET      /api/tasks
GET      /api/tasks/:taskId
POST     /api/tasks
PUT      /api/tasks/:taskId
DELETE   /api/tasks/:taskId
GET      /api/profile
</pre>

---

## Frontend Pages

<pre>
/               → Home/Dashboard  
/signup         → Signup page  
/login          → Login page  
/tasks/add      → Add new task  
/tasks/:taskId  → Edit a task  
</pre>

---

## npm scripts

**At root:**

* `npm run dev` → Run frontend + backend together
* `npm run dev-server` → Run backend only
* `npm run dev-client` → Run frontend only
* `npm run install-all` → Install all deps (root, frontend, backend)

**Frontend folder:**

* `npm start` → Start frontend (dev mode)
* `npm run build` → Build frontend (production)
* `npm test` → Run tests
* `npm run eject` → Eject configs

**Backend folder:**

* `npm run dev` → Start backend with nodemon
* `npm start` → Start backend normally

---

## Useful Links

**Official Docs**

* [React Docs](https://reactjs.org/docs/getting-started.html)
* [npm Docs](https://docs.npmjs.com/)
* [MongoDB Docs](https://docs.mongodb.com/manual/introduction/)
* [GitHub Docs](https://docs.github.com/en/get-started/quickstart/hello-world)

**Tutorials**

* [Express.js Basics](https://youtu.be/L72fhGm1tfE)
* [React Tutorial](https://youtu.be/EHTWMpD6S_0)
* [Redux Tutorial](https://youtu.be/1oU_YGhT7ck)

**Downloads**

* [Node.js](https://nodejs.org/)
* [VS Code](https://code.visualstudio.com/)

**Cheatsheets**

* [Git Cheatsheet](https://education.github.com/git-cheat-sheet-education.pdf)
* [VS Code Shortcuts](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf)
* [CSS Selectors Cheatsheet](https://frontend30.com/css-selectors-cheatsheet/)

---

👨‍💻 **Author:** Kamboji Venkata Subramanyam
GitHub: [@VenkataSubramanyamKamboji](https://github.com/VenkataSubramanyamKamboji)

```

---

👉 Do you want me to keep this **long detailed README** as your final version, or should I also prepare a **shorter manager-friendly README** (like a summary one-page)?
```
