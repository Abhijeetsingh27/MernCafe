# MernCafe ☕

A full-stack cafe management application built with the MERN stack (MongoDB, Express, React, Node.js).

## Overview

MernCafe is a modern web application designed for cafe management. It demonstrates a comprehensive full-stack implementation using JavaScript throughout the entire application, with a responsive and styled user interface.

## Tech Stack

- **Frontend**: JavaScript (76%), CSS (22.9%), HTML (1.1%)
- **Backend**: Node.js with Express.js
- **Database**: MongoDB
- **Architecture**: MERN Stack (MongoDB, Express, React, Node.js)

## Features

- User authentication and authorization
- Cafe menu management
- Order processing and tracking
- Real-time updates
- Responsive design for mobile and desktop
- Interactive user interface with React

## Getting Started

### Prerequisites

- Node.js and npm
- MongoDB (local or cloud instance)
- Git

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Abhijeetsingh27/MernCafe.git
cd MernCafe
```

2. Install backend dependencies:
```bash
cd backend
npm install
```

3. Install frontend dependencies:
```bash
cd ../frontend
npm install
```

4. Configure environment variables:
```bash
# Create a .env file in the backend directory
# Add your MongoDB connection string and other configuration
```

5. Start the backend server:
```bash
cd backend
npm start
```

6. In a new terminal, start the frontend development server:
```bash
cd frontend
npm start
```

The application will be available at `http://localhost:3000`.

## Project Structure

```
MernCafe/
├── backend/
│   ├── models/          # MongoDB schemas
│   ├── routes/          # API routes
│   ├── controllers/      # Business logic
│   ├── middleware/       # Custom middleware
│   └── server.js        # Express server entry point
├── frontend/
│   ├── src/
│   │   ├── components/   # React components
│   │   ├── pages/        # Page components
│   │   ├── styles/       # CSS stylesheets
│   │   └── App.js        # Main App component
│   └── public/           # Static assets
└── README.md            # This file
```

## Usage

### For Users
1. Sign up or log in to your account
2. Browse the cafe menu
3. Place orders
4. Track order status
5. Manage your profile

### For Admins
1. Manage cafe menu items
2. Process customer orders
3. View order history and analytics
4. Manage user accounts

## API Endpoints

The backend provides RESTful API endpoints for:
- User authentication (login, register, logout)
- Menu management (CRUD operations)
- Order management (create, read, update, delete)
- User profile management

## Contributing

Contributions are welcome! Please feel free to:
- Report bugs
- Suggest features
- Submit pull requests
- Improve documentation

To contribute:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is open source and available under the MIT License.

## Contact

For questions, feedback, or collaboration, reach out to [Abhijeetsingh27](https://github.com/Abhijeetsingh27).

---

**Enjoy managing your cafe!** ☕
