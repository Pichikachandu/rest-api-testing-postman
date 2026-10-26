# REST API Quality Engineering Platform

A complete MERN stack application for developing, testing, and validating REST APIs with integrated test case and defect management.

## Project Overview

This platform demonstrates practical knowledge of:
- REST APIs and HTTP methods
- Postman collections and automated API testing
- Positive, negative, and boundary test scenarios
- HTTP status codes and JSON response validation
- MongoDB CRUD operations
- React frontend development
- Node.js and Express.js backend development
- API error handling and input validation
- Git, GitHub, branches, and meaningful commit history

## Technology Stack

**Frontend:**
- React.js with Vite
- JavaScript
- HTML5 and CSS3
- Axios or Fetch API
- React Router

**Backend:**
- Node.js
- Express.js
- RESTful API architecture
- Mongoose

**Database:**
- MongoDB Community Server or MongoDB Atlas

**API Testing:**
- Postman
- Postman JavaScript test scripts
- Environment variables
- Collection Runner

## Project Structure

```
API_Guard/
├── backend/
│   ├── .env.example          # Environment variable template
│   ├── package.json          # Backend dependencies
│   ├── index.js              # Application entry point (to be added)
│   ├── models/               # Mongoose models (to be added)
│   ├── routes/               # API routes (to be added)
│   └── middleware/           # Custom middleware (to be added)
├── frontend/
│   ├── .env.example          # Environment variable template
│   ├── package.json          # Frontend dependencies
│   ├── src/
│   │   ├── components/       # React components
│   │   ├── pages/            # Page components
│   │   └── App.jsx           # Main App component
│   └── public/               # Static assets
├── .gitignore                # Git ignore rules
└── README.md                 # Project documentation
```

## Current Progress

- [x] Module 1: Project Initialization
- [ ] Module 2: Express Server and Health Check
- [ ] Module 3: MongoDB Integration
- [ ] Module 4: REST API CRUD Endpoints
- [ ] Module 5: Request Validation and Error Handling
- [ ] Module 6: Postman Collection
- [ ] Module 7: Automated API Test Execution
- [ ] Module 8: React Frontend
- [ ] Module 9: Test Case and Defect Management
- [ ] Module 10: Backend and Integration Testing
- [ ] Module 11: Documentation and Quality Review
- [ ] Module 12: Deployment and Final GitHub Release

## Setup Instructions

### Prerequisites
- Node.js (v18 or higher)
- MongoDB Community Server or MongoDB Atlas account
- Git
- Postman

### Initial Setup

1. Clone the repository:
```bash
git clone https://github.com/Pichikachandu/rest-api-testing-postman.git
cd API_Guard
```

2. Backend setup:
```bash
cd backend
npm install
cp .env.example .env
# Edit .env with your MongoDB connection string
```

3. Frontend setup:
```bash
cd frontend
npm install
cp .env.example .env
```

### Running the Application

Start the backend:
```bash
cd backend
npm start
```

Start the frontend:
```bash
cd frontend
npm run dev
```

## Development Workflow

Each module is completed, verified, and committed before moving to the next. Postman is used to test actual backend APIs, not just UI simulations.

## Git Commit History

1. chore: initialize MERN project structure
2. feat: add Express server and health check (pending)
3. feat: configure MongoDB connection (pending)
4. feat: implement item CRUD endpoints (pending)
5. feat: add request validation and error handling (pending)
6. test: add Postman collection and environment (pending)
7. test: add positive and negative API scenarios (pending)
8. test: add response validation scripts (pending)
9. feat: add API quality dashboard (pending)
10. feat: add test case and defect management (pending)
11. test: add backend integration tests (pending)
12. docs: document API test plan and execution (pending)
13. chore: prepare production deployment (pending)
14. release: publish version 1.0.0 (pending)

## License

ISC