# INSTALLATION Guide for NextCut

## Table of Contents
1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Clone the Repository](#clone-the-repository)
4. [Setting Up the Backend](#setting-up-the-backend)
    - [Install Dependencies](#install-dependencies)
    - [Environment Variables](#environment-variables)
    - [Running the Backend](#running-the-backend)
5. [Setting Up the Frontend](#setting-up-the-frontend)
    - [Install Frontend Dependencies](#install-frontend-dependencies)
    - [Running the Frontend](#running-the-frontend)
6. [Running the Application](#running-the-application)
7. [Common Issues](#common-issues)
8. [Conclusion](#conclusion)

## Introduction
This guide will help you set up the NextCut application locally. It covers both the frontend and backend, as well as the required dependencies.

## Prerequisites
Make sure you have the following software installed on your machine:
- Node.js (version 14.x or later)
- npm (Node package manager) or Yarn
- MongoDB (for backend)

## Clone the Repository
To get started, clone the repository to your local machine:
```bash
git clone https://github.com/abidtalha483-dev/NextCut.git
cd NextCut
```

## Setting Up the Backend
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

### Install Dependencies
Run the following command to install the backend dependencies:
```bash
npm install
```

### Environment Variables
Create a `.env` file in the backend directory based on the `.env.example` file. Make sure to fill in all necessary variables such as:
- `MONGO_URI`
- `PORT`

### Running the Backend
Once you've set up the environment variables, you can start the backend server:
```bash
npm start
```

## Setting Up the Frontend
1. Navigate to the frontend directory:
   ```bash
   cd ../frontend
   ```

### Install Frontend Dependencies
Run the following command to install the frontend dependencies:
```bash
npm install
```

### Running the Frontend
Start the frontend development server:
```bash
npm start
```

## Running the Application
Now that both the backend and frontend are running, you can visit the application at `http://localhost:3000` (or the port specified in the backend).

## Common Issues
- If you encounter any issues starting the backend, ensure that MongoDB is running and that your connection string in the `.env` file is correct.
- In case of frontend issues, double-check that all dependencies were installed correctly.

## Conclusion
You should now have a fully functional local setup of NextCut. For any further assistance, feel free to reach out to the maintainer or check the GitHub issues page.