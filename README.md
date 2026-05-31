# The Data Hub API

## Project Overview

The Data Hub API is a simple REST API built using Node.js and Express.js. This project was created as part of Sprint 09 to understand backend development concepts such as routing, middleware, CRUD operations, and API testing.

The API manages blog posts using an in-memory array instead of a database.

---

## Features

- Get all blog posts
- Get a single blog post by ID
- Create a new blog post
- Update an existing blog post
- Delete a blog post
- Custom request logging middleware
- Mock login endpoint
- JSON request and response handling

---

## Technologies Used

- Node.js
- Express.js
- Nodemon
- Postman

---

## Installation

Clone the repository:

```bash
git clone <repository-url>
```

Move into the project folder:

```bash
cd Prodesk-Mission-9
```

Install dependencies:

```bash
npm install
```

Start the server:

```bash
npm run dev
```

---

## API Endpoints

### Home Route

GET /

Returns API status.

### Blog Routes

GET /posts

Returns all posts.

GET /posts/:id

Returns a single post.

POST /posts

Creates a new post.

Example Body:

```json
{
  "title": "My First Blog",
  "content": "Learning Express.js"
}
```

PUT /posts/:id

Updates an existing post.

DELETE /posts/:id

Deletes a post.

---

### Login Route

POST /login

Example Body:

```json
{
  "username": "admin",
  "password": "1234"
}
```

Returns:

```json
{
  "token": "mock-jwt-token"
}
```

---

## Running Locally

```bash
npm install
npm run dev
```

Server runs on:

http://localhost:5000

---

## Deployment

Live URL:

[(Add Render URL Here)](https://prodesk-mission-9.onrender.com/)

A TEJASYA
P/IL/26/NOIDA/M1299

## Author

Sprint 09 Submission
