# cs-helper-web-app

CSHelper is a MERN stack web application built for computer science students. It includes real-time chat, a Q&A forum, and an online assessment practice environment with support for multiple programming languages.

## Features

- real-time chat using Socket.IO
- Q&A forum for posting questions and answers
- online assessment practice playground similar to LeetCode
- support for JavaScript, Python, and Java code execution
- automatic unit test runner
- solution reveal mode
- OpenAI powered chatbot for hints and debugging
- profile image and media upload using Cloudinary

## Tech Stack

frontend
- React
- Vite
- DaisyUI
- Zustand
- JavaScript
- Tailwind CSS

backend
- Node.js
- Express
- MongoDB
- Mongoose
- Socket.IO
- Cloudinary
- JSON Web Tokens

## Running the Project

1. install dependencies

npm install


2. build the project

npm run build


3. start backend

cd backend
npm run dev


4. start frontend

cd frontend
npm run dev


## Environment Variables

Create a `.env` file in the root and include the following:

PORT=

MONGODB_URI=

JWT_SECRET=

CLOUDINARY_CLOUD_NAME=

CLOUDINARY_API_KEY=

CLOUDINARY_API_SECRET=

OPENAI_API_KEY=

NODE_ENV=development


## Purpose

CSHelper is designed to support CS majors by giving them a place to study, practice skills, ask questions, and collaborate with others. It provides tools for learning, communication, and coding all in one platform.

