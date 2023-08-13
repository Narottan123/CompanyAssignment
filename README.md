
---

# Company Website - README

This repository contains the source code for a company website built using React, Node.js, Express, and MongoDB. 
The website features a responsive navigation bar with tabs for company profile, user details form, and project information retrieved 
from an API.

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine
- MongoDB database connection

### Installation

1. Clone the repository:

   git clone https://github.com/Narottan123/CompanyAssignment.git
   cd assiggnment -->Frontend
   cd backend -->Backend
   

3. Install dependencies for both frontend and backend:

  
   # Inside the root directory
   npm install

   # Navigate to the client directory (frontend)
   cd assignment
   npm install
   ```



### Running the Application

1. Start the backend server (Node.js and Express):

   
   # Inside the backend directory
   nodemon index.js
   ```

2. Start the frontend development server (React):

  
   # Inside the assignment directory
   npm start
   ```

3. Open your browser and navigate to `http://localhost:3000` to view the company website.

## Features

- Responsive Navigation Bar with Logo and Tabs (HomePage)
- Company Profile Tab: Display information about the company(AboutPage)
- User Details Form Tab: Collect user details and post to MongoDB(ContactPage)
- Projects Tab: Display project information fetched from API(ProjectPage)

## Technology Stack

- Frontend: React
- Backend: Node.js, Express
- Database: MongoDB

## API Endpoints

- POST `/api/data`: Post user details to MongoDB
- GET `/api/projectdetail`: Get project information


