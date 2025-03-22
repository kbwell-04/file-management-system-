# File Management System

This is a file management system developed using **React** (with **Yarn** for package management) for the frontend and **Node.js** for the backend. The system allows users to manage their files based on their roles and permissions.

## Features

- **User Login & Role-based Permissions**  
  Users can log in and access features based on their role. Each role has specific permissions related to file management and interactions with other users.

- **File Management**  
  - Users can store files in their preferred folder.
  - Ability to create, delete, and edit folders.
  - Users can rename, open, and download their own files.

- **Messaging System**  
  Users can send messages to other users based on their username. Messages can be sent with or without attached files.

## Setup and Installation

### Prerequisites

- **Node.js**: Ensure that Node.js is installed on your machine.
- **Yarn**: Ensure that Yarn is installed for package management.

### Backend (Node.js)

1. Navigate to the backend directory and install dependencies:
   ```sh
   cd backend
   yarn install
