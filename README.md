# Grocery API

A production-grade RESTful backend API for grocery e-commerce, built with strict layered architecture and design patterns.

## Features

- Layered architecture with domain/data/presentation/common separation
- Dependency injection via tsyringe IoC container with TypeScript decorators
- JWT authentication with bcrypt password hashing
- Product, category, and order management APIs with full CRUD
- Cloudinary image upload with Multer middleware
- Auto-generated Swagger UI documentation from Mongoose schemas
- Request validation with Joi schemas
- Security headers via Helmet and CORS configuration

## Tech Stack

- Node.js, Express, TypeScript
- MongoDB, Mongoose
- JWT, bcrypt
- Cloudinary, Multer
- Joi, Swagger
- tsyringe (DI container)
- Helmet

## Setup

1. Clone the repo
2. Run `npm install`
3. Create a `.env` file with MongoDB URI, JWT secret, and Cloudinary credentials
4. Run `npm run dev`
5. Open Swagger UI at `http://localhost:3000/api-docs`

## Author

**Prasad Rawas** - [GitHub](https://github.com/prasadrawas)

