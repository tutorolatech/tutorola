# Tutorola code
- This repository contains both the frontend and backend code
.

## About the app
Actually, there are two separated apps. The frontend directory which serves the FrontEnd (using React), and the backend directory which serves the BackEnd (in Node/Express).

## Setup
1. Download and install the latest stable version of node.js if you haven't already from https://nodejs.org/en/download/
2. Download and install xampp from https://www.apachefriends.org/index.html
3. Clone the repository in your local machine.

## How to setup the Database
1. Open phpMyAdmin after configuring and starting the Apache and MySQL server in xampp
2. Create a new Database named tutorola
3. Create a new Table named students
4. The Table students will have 5 columns: id, email, phoneNumber, username, password (all case sensitive).
5. Set id as the primary key and check the AUTO_INCREMENT (A_I) checkbox
6. Repeat the steps 3, 4, 5 for a table with name teachers

## How to run the Backend
1. In your terminal, navigate to the `backend` directory.
2. Run `npm install` to install all dependencies.
3. Run `npm start` to start the app.

## How to run the Frontend
1. In another terminal, navigate to the `frontend` directory.
2. Run `npm install` to install all dependencies.
3. Run `npm start` to start the app
