

---

# Company Website

This repository contains the source code for a company website built using React, Node.js, Express, and MongoDB. The website features a responsive navigation bar with tabs for company profile, user details form, and project information retrieved from an API.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [API Endpoints](#api-endpoints)

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine
- MongoDB database connection

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Narottan123/CompanyAssignment.git
   cd CompanyAssignment
   ```

2. Install dependencies for both frontend and backend:

   ```bash
   # Install backend dependencies
   cd backend
   npm install

   # Install frontend dependencies
   cd ../assignment
   npm install
   ```

### Running the Application

1. Start the backend server (Node.js and Express):

   ```bash
   # Inside the backend directory
   nodemon index.js
   ```

2. Start the frontend development server (React):

   ```bash
   # Inside the assignment directory
   npm start
   ```

3. Open your browser and navigate to `http://localhost:3000` to view the company website.

## Features

- **Responsive Navigation Bar**: The homepage features a navigation bar with a logo and tabs.
- **Company Profile Tab**: The About page displays information about the company.
- **User Details Form Tab**: The Contact page collects user details and posts them to MongoDB.
- **Projects Tab**: The Project page displays project information fetched from the API.

## Technology Stack

- **Frontend**: React
- **Backend**: Node.js, Express
- **Database**: MongoDB

## API Endpoints

- **POST** `/api/data`: Post user details to MongoDB
- **GET** `/api/projectdetail`: Get project information

