# Namma Yatri POC App

A modern, user-friendly transportation application designed to connect riders with drivers efficiently. Namma Yatri provides a seamless experience for booking rides, tracking journeys, and making payments.

## Project Structure

The project is organized into two main components:

- **Frontend**: User interface and client-side logic
- **Backend**: Server-side logic, API endpoints, and database interactions

## Features

- User authentication and profile management
- Real-time ride booking and tracking
- Multiple payment options
- Driver and rider rating system
- Trip history and receipts
- Location-based services

## Technology Stack

### Frontend
- React/React Native for cross-platform mobile development
- Redux for state management
- Mapbox/Google Maps for location services
- Material UI/Tailwind CSS for styling

### Backend
- Node.js/Express.js for API development
- MongoDB/PostgreSQL for database
- JWT for authentication
- Socket.io for real-time communication
- Payment gateway integrations

## Installation

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- MongoDB/PostgreSQL

### Backend Setup
```bash
# Navigate to the backend directory
cd backend

# Install dependencies
npm install

# Create .env file with required environment variables
# See .env.example for reference

# Start the server
npm run dev
```

### Frontend Setup
```bash
# Navigate to the frontend directory
cd frontend

# Install dependencies
npm install

# Create .env file with required environment variables
# See .env.example for reference

# Start the development server
npm start
```

## Usage

After setting up both frontend and backend, you can access:
- Web application: http://localhost:3000
- API endpoints: http://localhost:5000/api

## API Documentation

The API documentation is available at `/api/docs` when the backend server is running.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request


## Acknowledgments

- Inspired by the original Namma Yatri service in Bangalore
- Thanks to all members of git gud who have helped shape this project 