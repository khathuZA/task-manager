# Task Manager App

A full-stack task management application built with React, Node.js, Express, and MongoDB.

> 🚧 **Work in Progress** — Backend complete. Frontend coming soon.

## Tech Stack

- **Frontend:** React (Vite) — in progress
- **Backend:** Node.js, Express
- **Database:** MongoDB Atlas
- **Authentication:** JWT (JSON Web Tokens)

## Features

- User registration and login
- JWT-based authentication
- Create, read, update and delete tasks
- Each user only sees their own tasks
- Task status tracking (todo / in-progress / done)

## Backend API Endpoints

| Method | Endpoint | Description | Auth Required |
|--------|----------|-------------|---------------|
| POST | `/api/auth/register` | Register a new user | No |
| POST | `/api/auth/login` | Login and get token | No |
| GET | `/api/tasks` | Get all tasks | Yes |
| POST | `/api/tasks` | Create a task | Yes |
| PUT | `/api/tasks/:id` | Update a task | Yes |
| DELETE | `/api/tasks/:id` | Delete a task | Yes |

## Project Status

- [x] Backend API
- [x] User authentication
- [x] Task CRUD endpoints
- [ ] React frontend
- [ ] Frontend connected to API
- [ ] Deployment

## Author

**Khathutshelo** — Final year BTech Computer Science student at TUT
