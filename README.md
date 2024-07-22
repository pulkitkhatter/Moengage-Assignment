# Dog Haven

This is an assingment given by Moengage in which we can fetch dog images using https responses 

## Getting Started

These instructions will help you set up and run the `dogwebsite` and `mern-auth` projects on your local machine.

### Prerequisites

Ensure you have the following software installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

### Installation

1. **Download the ZIP file**

   Download the ZIP file from the repository and extract it.

2. **Navigate to the Project Directories**

   Open a terminal and change the directory to each project folder.

 
```bash
#!/bin/bash

# Start the Backend Server
echo "Starting backend server..."
cd path/to/mern-auth
npm install
nodemon server.js &

# Start the Frontend Server
echo "Starting frontend server..."
cd ../dogwebsite
npm install
npm start
