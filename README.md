# Full-Stack Note-Taking Application (CRUD API + Frontend)
![App Screenshot]()  

A complete Note-Taking application built using **Node.js**, **Express.js**, **MySQL**, and **Vanilla JavaScript**.  
This project provides a **RESTful CRUD API** for backend operations and a responsive frontend to manage notes seamlessly.

---

## Features

- Create new notes with title & content
- View all notes or a specific note by ID
- Load an existing note for editing & update it
- Delete notes when no longer needed
- Responsive frontend with clean UI
- Secure backend with validation & error handling
- Optimized MySQL queries & connection pooling
- Health check endpoint for monitoring database connection

---

![Note-Taking App Demo](https://i.pinimg.com/originals/8d/62/1f/8d621f66f551b6a39072473d52280ff0.gif)  

---

## Tech Stack

**Backend:**
- Node.js
- Express.js
- MySQL
- Express-Validator
- CORS

**Frontend:**
- HTML
- CSS
- JavaScript (Fetch API for backend calls)

**Database:**
- MySQL (with connection pooling & health checks)

---

## API Endpoints

| Method | Endpoint         | Description                   |
|--------|-----------------|--------------------------------|
| GET    | `/notes`        | Get all notes                  |
| GET    | `/notes/:id`    | Get note by ID                 |
| POST   | `/notes`        | Create new note                |
| PUT    | `/notes/:id`    | Update existing note           |
| DELETE | `/notes/:id`    | Delete note                    |

---

