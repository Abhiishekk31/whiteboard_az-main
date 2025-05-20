# Whiteboard Application

A real-time collaborative whiteboard application built with React, Node.js, and Socket.IO. This application allows multiple users to draw, collaborate, and share ideas in real-time on a digital whiteboard.

## Features

- Real-time collaborative drawing
- Multiple drawing tools and colors
- User authentication and authorization
- Responsive design with Tailwind CSS
- Smooth drawing experience using Perfect Freehand
- Real-time updates using Socket.IO

## Tech Stack

### Frontend
- React.js
- Tailwind CSS for styling
- Socket.IO Client for real-time communication
- Perfect Freehand for smooth drawing
- RoughJS for sketchy drawing effects
- React Router for navigation
- Axios for API requests

### Backend
- Node.js with Express
- MongoDB with Mongoose
- Socket.IO for real-time communication
- JWT for authentication
- Bcrypt for password hashing

## Project Structure

```
├── whiteboard-tutorial/    # Frontend React application
│   ├── public/            # Static files
│   ├── src/              # React source code
│   └── package.json      # Frontend dependencies
│
└── backend/              # Backend Node.js application
    ├── config/          # Configuration files
    ├── controllers/     # Route controllers
    ├── middlewares/     # Custom middlewares
    ├── models/         # Database models
    ├── routes/         # API routes
    └── server.js       # Main server file
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd whiteboard-application
```

2. Install frontend dependencies:
```bash
cd whiteboard-tutorial
npm install
```

3. Install backend dependencies:
```bash
cd ../backend
npm install
```

4. Create a `.env` file in the backend directory with the following variables:
```
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```

### Running the Application

1. Start the backend server:
```bash
cd backend
npm start
```

2. Start the frontend development server:
```bash
cd whiteboard-tutorial
npm start
```

The application will be available at `http://localhost:3000`

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Perfect Freehand for the smooth drawing experience
- RoughJS for the sketchy drawing effects
- Socket.IO for real-time communication capabilities
