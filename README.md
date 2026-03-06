# Auth API (Node.js + Express + MongoDB + Docker)

A secure authentication REST API built using Node.js, Express, MongoDB and Docker.

## Features
- User Registration
- User Login
- JWT Authentication
- Token Blacklisting (Logout)
- Protected Routes
- Dockerized Application

## Tech Stack
- Node.js
- Express.js
- MongoDB
- JWT
- Docker

## Run Locally

git clone https://github.com/yourusername/auth-api.git

npm install

npm start

## Run with Docker

docker build -t auth-api .

docker run -p 5000:5000 auth-api

## API Endpoints

POST /api/auth/register
Register a new user

POST /api/auth/login
Login user

POST /api/auth/logout
Logout user (blacklist token)

GET /api/protected
Access protected route

GET/api/auth/me
Get current User

PUT/api/auth/update-profile
Update Profile

PUT/api/auth/change-password
Change Password

DELETE/api/auth/delete-account
Delete acount

GET/api/auth/admin
Admin route

## Project Structure

auth-api
│
├── config
│   └── db.js
│
├── controllers
│   └── authController.js
│
├── middleware
│   └── authMiddleware.js
│
├── models
│   ├── User.js
│   └── BlacklistedToken.js
│
├── routes
│   └── authRoutes.js
│
├── server.js
├── Dockerfile
├── .dockerignore
├── package.json


Installation

Clone the repository

git clone https://github.com/your-username/auth-api.git

Install dependencies

npm install
