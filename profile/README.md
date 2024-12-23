# Sharepeare

A social media platform for unleashing your shakespeare.

This is a comprehensive MERN Stack social media application that allows users to create and like posts. This full-stack application is built using MongoDB, Express.js, React.js, Node.js (MERN) for the backend, Redux for state management, and Material-UI (MUI) for a modern and intuitive interface. User authentication is managed using JSON Web Tokens (JWT) and password encryption is implemented using Bcrypt.

## Features
- Users can create new posts
- Like a post
- User authentication using JWT
- Password encryption with Bcrypt

## Future Features
- Commenting on posts
- Messaging between users

## Tech Stack
- MongoDB
- Express.js
- React.js
- Node.js
- Redux
- Material-UI
- JWT
- Bcrypt

## Requirements
- Node.js (version 18.16.1)
- MongoDB (local or cloud)
- Yarn or npm

## Installation

1. Clone these repositories
```
git clone https://github.com/sharespeare/sharespeare-frontend.git
```
```
git clone https://github.com/sharespeare/sharespeare-backend.git
```

2. Install backend dependencies
```
cd server
npm install
```
or
```
cd server
yarn install
```

3. Install frontend dependencies
```
cd ../client
npm install
```
or
```
cd ../client
yarn install
```

## Usage

1. Run the server server from the server directory
```
npm start
```
or
```
yarn start
```

2. Run the client server from the client directory
```
npm start
```
or
```
yarn start
```

Open [http://localhost:3000](http://localhost:3000) to view the application in your browser.

## API Endpoints
- User Registration: POST /api/users/register
- User Login: POST /api/users/login
- Create a Post: POST /api/posts/create
- Like a Post: PUT /api/posts/:postId/like
