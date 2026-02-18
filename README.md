# News Publishing Web Application (Learning Project)

## Project Goal
This project is a real-world learning application built to understand full-stack development architecture.

The application allows:
- Users to register and log in
- Users to browse news/posts
- Admin to create and manage posts
- Posts to be organized by categories

This project focuses on backend learning, API design, authentication, and frontend-backend integration.

---

## Tech Stack

### Frontend
React (JavaScript)

### Backend
FastAPI (Python)

### Database
PostgreSQL (SQLite for local development)

### Authentication
JWT-based authentication

### Version Control
Git + GitHub

---

## Application Roles

### Admin
- Login
- Create posts
- Edit posts
- Delete posts
- Create categories

### User
- Register
- Login
- View posts
- Search posts
- Filter by category

---

## MVP Features (Version 1)

### Authentication
- User registration
- User login
- JWT token generation

### Posts
- View all posts
- View post details
- Admin CRUD operations

### Categories
- Create category (admin)
- List categories

### Search
- Search posts by title

---

## Database Schema

### Users
- id
- username
- email
- password_hash
- role (admin/user)
- created_at

### Categories
- id
- name
- created_at

### Posts
- id
- title
- content
- category_id
- created_by
- created_at

---

## API Design

### Auth APIs
POST /register  
POST /login  

### Public APIs
GET /posts  
GET /posts/{id}  
GET /categories  

### Admin APIs
POST /posts  
PUT /posts/{id}  
DELETE /posts/{id}  
POST /categories  

---

## High-Level Architecture

React Frontend  
↓  
FastAPI Backend (REST APIs)  
↓  
PostgreSQL Database  

---

## Learning Objectives
This project is intended to teach:

- REST API development
- Backend architecture
- Database schema design
- Authentication using JWT
- Role-based authorization
- Frontend-backend integration
- Deployment basics
- Git workflow

---

## Future Enhancements (Not MVP)

- Comments system
- Likes/bookmarks
- Pagination
- Image uploads
- Admin dashboard UI
- Docker support
- Caching
- AI-powered summarization of posts

---

## Development Phases

Phase 1 — Project setup  
Phase 2 — Database models  
Phase 3 — Authentication  
Phase 4 — Posts & categories APIs  
Phase 5 — Frontend UI  
Phase 6 — Integration  
Phase 7 — Deployment  

---

## Project Status
Planning Phase