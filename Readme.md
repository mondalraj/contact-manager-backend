# CONTACT MANAGER API

## Description

A simple contact manager API built with Node.js, Express.js and MongoDB with Authentication, Authorization, JWT, Middlewares, Protected Routes, Mongoose, DB Relationships.

### APIs

Public Routes

- [x] Register User (POST /api/users/register)
- [x] Login User (POST /api/users/login)

Protected Routes (Need to be logged in to access)

- [x] Get Logged In User (GET /api/users/current)
- [x] Get All Contacts (GET /api/contacts)
- [x] Add New Contact (POST /api/contacts)
- [x] Update Contact (PUT /api/contacts/:id)
- [x] Delete Contact (DELETE /api/contacts/:id)

## Installation and Usage

```bash
# Install dependencies
npm install

# Serve on localhost:5000
npm run dev (nodemon)

# Build for production
npm run build
```
