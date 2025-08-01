# Dialectica - Structured Debate Platform

Dialectica is a real-time web application designed to facilitate structured debates and discussions. It enables users to engage in meaningful conversations with a moderated format, supporting both participants and administrators.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Configuration](#configuration)
- [Deployment](#deployment)
- [Project Structure](#project-structure)
- [License](#license)
- [Contributing](#contributing)
- [Community & Support](#community--support)

## Features

- **User Authentication**: Secure registration and login using JWT.
- **Admin Dashboard**: Manage users, debates, and platform settings.
- **Debate Rooms**: Real-time, moderated debate environments.
- **User Profiles**: Customizable profiles with statistics and achievements.
- **Real-time Messaging**: Instant communication via Socket.io.
- **Responsive Design**: Optimized for desktop and mobile.
- **Statistics Tracking**: User performance and engagement metrics.

## Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB (via Mongoose)
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Real-time**: Socket.io
- **Authentication**: JWT

## Getting Started

### Prerequisites

- Node.js (v14+ recommended)
- npm
- MongoDB (local or Atlas)

### Installation

1. **Clone the repository**
   ```sh
   git clone https://github.com/yourusername/dialectica.git
   cd dialectica
   ```

2. **Install dependencies**
   ```sh
   npm install
   ```

3. **Configure environment variables**

   Create a `.env` file in the root directory:
   ```
   JWT_SECRET=your_jwt_secret
   MONGODB_URI=your_mongodb_connection_string
   PORT=5000
   ```

4. **Start the application**
   ```sh
   npm start
   ```

5. **Development mode (auto-restart)**
   ```sh
   npm run dev
   ```

## Configuration

- **Database**: Update `MONGODB_URI` in `.env` for your MongoDB connection.
- **JWT Secret**: Set a strong secret in `JWT_SECRET`.
- **Port**: Default is `5000`, can be changed in `.env`.

## Deployment

Dialectica can be deployed on:

- **Render**: Free tier, GitHub integration.
- **Railway**: $5 free credit/month.
- **Fly.io**: Free tier with multiple VMs.
- **MongoDB Atlas**: Free cloud database.

See platform documentation for deployment steps.

## Project Structure

```
Diel-MERN/
├── config/           # Database configuration
├── middleware/       # Auth and admin middleware
├── models/           # Mongoose models (User, UserStats)
├── public/           # Static frontend files (HTML, CSS, JS, images)
├── routes/           # Express route handlers
├── server.js         # Main server entry point
├── package.json      # Project metadata and scripts
└── README.md         # Project documentation
```

## License

Boost Software License - Version 1.0 - August 17th, 2003

## Contributing

We welcome contributions! Please follow these steps:

1. **Fork the repository**
2. **Create a new branch**
   ```sh
   git checkout -b feature/your-feature
   ```
3. **Commit your changes**
   ```sh
   git commit -m "Add your feature"
   ```
4. **Push to your branch**
   ```sh
   git push origin feature/your-feature
   ```
5. **Open a Pull Request** on GitHub

### Guidelines

- Write clear, descriptive commit messages.
- Follow existing code style and conventions.
- Add tests for new features when possible.
- Document your changes in the README if relevant.

## Community & Support

Join our Discord server for help, discussions, and collaboration:

**Discord:** [https://discord.gg/uc2AHnBd](https://discord.gg/uc2AHnBd)

GSSoC 25 contributors and mentors are welcome for better coordination and communication.

## Installation

1. Clone the repository
   ```
   git clone https://github.com/yourusername/dialectica.git
   cd dialectica
   ```

2. Install dependencies
   ```
   npm install
   ```

3. Create a `.env` file in the root directory with the following variables:
   ```
   JWT_SECRET=your_jwt_secret
   MONGODB_URI=your_mongodb_connection_string
   PORT=5000
   ```

4. Start the application
   ```
   npm start
   ```

5. For development with auto-restart:
   ```
   npm run dev
   ```

## Deployment

This application can be deployed on various platforms:

- **Render**: Free tier with automatic deployments from GitHub
- **Railway**: Simple deployment with $5 free credit per month
- **Fly.io**: Free tier with 3 shared-cpu-1x 256mb VMs

For the database, MongoDB Atlas provides a free tier that works well with this application.

## License

Boost Software License - Version 1.0 - August 17th, 2003


# Contributing
We welcome contributions to CreateMVP! Here's how you can contribute:

## General Contributions

1. Fork the repository
2. Create a new branch for your feature (git checkout -b feature/amazing-feature)
3. Commit your changes (git commit -m 'Add some amazing feature')
4. Push to the branch (git push origin feature/amazing-feature)
5. Open a Pull Request

## Discord Server
GSSoC 25 contributors and mentors . please join my dc server for better coordination and communication .

link : https://discord.gg/uc2AHnBd
