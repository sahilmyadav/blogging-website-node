# Blogging Website (Node.js)

A blogging website built with Node.js, Express and EJS. Users can sign up,
write blog posts with images, and read posts from other authors.

## Features

- User authentication with JWT and cookies
- Create and publish blog posts
- Image uploads with Multer
- Server-side rendered pages with EJS templates
- MongoDB storage via Mongoose

## Tech Stack

- Node.js, Express, EJS
- MongoDB / Mongoose
- jsonwebtoken, cookie-parser, multer

## Getting Started

```bash
npm install
npm start
```

For development with auto-reload:

```bash
npm run dev
```

Add your MongoDB connection string and JWT secret in the environment/config
before starting.

## Project Structure

```
routes/       App and API routes
models/       Mongoose models
middleware/   Auth and helper middleware
services/     Business logic helpers
views/        EJS templates
index.js      Server entry point
```
