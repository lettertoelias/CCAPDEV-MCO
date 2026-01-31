# Restaurant Review Web Application

## Overview

A full-stack restaurant review web application that allows users to discover restaurants (although limited to only the restaurants available in the project database) , submit reviews, upload images, and interact through comments, favorites, and bookmarks. The platform supports **role-based access**, providing separate experiences for regular reviewers and administrators.

This project was built as a **team collaboration**, with my primary contribution focused on **frontend design and implementation**, emphasizing clean UI, responsive layouts, and dynamic DOM-driven updates using vanilla HTML, CSS, and JavaScript.

---

## Tech Stack

### Frontend

* Vanilla **HTML**, **CSS**, and **JavaScript** (no frontend frameworks)
* Server-side templating with **Handlebars (express-handlebars)**
* Responsive layout and DOM manipulation

### Backend

* **Node.js** with **Express.js**
* **MongoDB** for data persistence
* **Passport.js** for authentication and role-based authorization
* **Express-session** for session management

### Supporting Libraries & Tools

* `method-override` for RESTful routing
* `express-flash` for user feedback messages
* `dotenv` for environment configuration

---

## Core Features

* User authentication with **sign-up and login** functionality
* Role-based access control for **reviewers** and **administrators**
* Dynamic restaurant review submission and rendering
* Image uploads associated with restaurants and reviews
* Commenting and reply functionality
* Favorites and bookmarks with persistent storage
* Admin-specific views and management capabilities
* Data-driven UI updates reflecting real-time database changes

---

## Architecture & Implementation

* Implemented a **server-rendered architecture** using Express and Handlebars
* Frontend logic relies on **vanilla JavaScript** for DOM manipulation and client-side validation
* RESTful routes handle CRUD operations for reviews, images, comments, and user interactions
* Authentication and authorization managed with Passport.js strategies
* MongoDB used to persist users, roles, reviews, media, and interactions

---

## Live Deployment

The application is deployed and publicly accessible on Render:

🔗 [https://munch-1zaq.onrender.com/](https://munch-1zaq.onrender.com/)

The deployed version includes full authentication, role-based views for reviewers and administrators, and dynamic content backed by a MongoDB database.

> Note: This repository reflects a production-deployed application. Local setup instructions are not currently documented.

---

## Project Status

✅ **Complete** — core features implemented and fully functional

---

## Attribution

This repository is a **fork of the original team project repository**.
I contributed primarily as a **frontend developer**, focusing on UI/UX design, responsive layouts, and client-side logic using vanilla HTML, CSS, and JavaScript. Backend development was completed collaboratively using Node.js, Express, and MongoDB.

---

## Notes for Reviewers

This project intentionally avoids frontend frameworks to demonstrate strong fundamentals in core web technologies, DOM manipulation, and full-stack integration.
