# MindFlow

A full-stack note-taking application built with Express, MongoDB, React, and Tailwind CSS. This application allows users to create an account, log in, and manage their notes, with features like adding, editing, deleting, and pinning notes. Users can also search through their notes and manage note visibility with a pinning feature.

## Features
- User authentication (Signup and Login)
- Create, edit, delete, and view notes
- Pin/unpin notes for easy access
- Search functionality for notes
- Secure routes with JWT authentication

## Tech Stack
- Frontend:
    - **React**: Frontend library for building the user interface.
    - **React Router**: Client-side routing.
    - **Tailwind CSS**: Utility-first CSS framework for styling.
- Backend:
    - **Express**: Web framework for Node.js.
    - **MongoDB**: NoSQL database for storing user and note data.
    - **Mongoose**: ODM for MongoDB.
    - **JWT**: JSON Web Tokens for user authentication and authorization.

## Installation
To run this project locally, follow these steps:

### Backend:
Clone the repository:

1. Copy code
```bash
git clone https://github.com/your-username/notes-app.git
cd notes-app/server
```

2. Install the dependencies:
```bash
npm install
```

3. Set up the environment variables:
Create a `.env` file in the `server/` directory with the following content:
```bash
ACCESS_TOKEN_SECRET=yourSecretKey
```

4. Add your MongoDB connection string in config.json:
```bash
{
   "connectionString": "mongodb://localhost:27017/your-database-name"
}
```

5. Start the server:
```bash
npm start
```


### Frontend:
1. Navigate to the `client/` directory:
```bash
cd ../client
```

2. Install the dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```
Open the app in your browser at http://localhost:3000.