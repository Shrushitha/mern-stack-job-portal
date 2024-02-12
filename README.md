# MERN Stack Job Portal

Welcome to the MERN Stack Job Portal! This project is a full-stack application designed to connect employers with potential job candidates. Built with MongoDB, Express.js, React.js, and Node.js, it features a robust backend API and a dynamic frontend interface.

## Features

### Job Listings: Employers can post job openings with detailed descriptions, and job seekers can browse through available listings.\
### User Authentication: Secure signup/login functionality for both job seekers and employers.\
### Profile Management: Users can create and edit their profiles to include relevant information.\
### Application System: Job seekers can apply directly through the portal, and employers can review applications.\
### Search and Filter: Advanced search options allow users to filter job listings by keywords, location, job type, and more.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites
Node.js\
npm\
MongoDB\

## Installation
## Clone the repository 
git clone 

npm start\
## Set up the Frontend
In a new terminal window, navigate to the frontend directory, install dependencies, and start the React app:\
cd frontend\
npm install\
npm start

## Set up the Backend
Navigate to the backend directory, install dependencies, and start the server:


cd backend\
npm install\
npm start\


Environment Variables\
Create a .env file in the backend directory and add the following variables:\

## env
MONGO_URI=your_mongodb_uri\
JWT_SECRET=your_jwt_secret\
PORT=5000\
Replace your_mongodb_uri and your_jwt_secret with your actual MongoDB URI and JWT secret.\

## Usage
After starting both the backend and frontend servers, visit http://localhost:3000 in your browser to view the job portal application.
