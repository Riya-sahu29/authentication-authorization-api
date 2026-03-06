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
