# User Service - Personalized Notification System

This service manages user registration, preferences, and authentication using JWT.

## Features

- Register a new user with preferences
- Update user notification preferences
- Fetch user details
- JWT authentication

## Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT

## Endpoints

| Method | Endpoint            | Description                        |
|--------|---------------------|------------------------------------|
| POST   | `/register`         | Register a new user                |
| PUT    | `/preferences/:id`  | Update user preferences            |
| GET    | `/user/:id`         | Fetch user details                 |

## Setup Instructions

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/personalized-notification-system.git
   cd user-service
