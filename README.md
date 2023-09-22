# BeyondBonds - Social Media App

BeyondBonds is a social media app built using the MERN stack (MongoDB, Express.js, React, Node.js). It allows users to connect and share their experiences with friends and family.

## Project Structure

This project is organized into two main folders: `client` and `server`.

- **`client`**: Contains the front-end code for the React application.
- **`server`**: Contains the back-end code for the Node.js server and API.

## Installation

To get started with BeyondBonds, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/beyondbonds.git
   cd beyondbonds
   ```

2. Install npm dependencies of `concurrently` which will furter use for client and server:

   ```bash
   npm install
   ```

## Configuration

Before running the server, make sure to set up your environment variables in the `.env` file located in the `server` folder. You need to provide the following configurations:

```env
MONGO_URL = your mongo db url 
PORT=3001
JWT_SECRET='superseceret'
```

## Usage

To start the application, you can use the following npm scripts:

1. To concurrently install dependencies for both the client and server:

   ```bash
   npm run devall
   ```

2. To start the React app and server concurrently:

   ```bash
   npm run dev
   ```

   This command will start the React app on port 3000 and the server on port 3001. You can access the application by opening your web browser and navigating to `http://localhost:3000`.

## Contributing

If you'd like to contribute to BeyondBonds, Contribute to it



Feel free to reach out if you have any questions or need further assistance.
