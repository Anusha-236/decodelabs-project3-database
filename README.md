# decodelabs-database-integration

Full Stack Project 3: Database Integration using Node.js, Express.js, MongoDB, and Mongoose.

## Features
- Express server with `express.json()` middleware
- MongoDB connection via Mongoose
- MVC structure: models, controllers, routes, config
- Student Management REST API (CRUD)

## Requirements
- Node.js >=14
- MongoDB instance (local or remote)

## Setup

1. Install dependencies

```powershell
npm install
```

2. Create `.env` from the example and set `MONGO_URI` if needed

```powershell
copy .env.example .env
# edit .env to set your MongoDB URI
```

3. Start the server

```powershell
npm start
# or for development with auto-reload:
npm run dev
```

## API Endpoints

- `GET /students` - list all students
- `GET /students/:id` - get student by id
- `POST /students` - create student
- `PUT /students/:id` - update student
- `DELETE /students/:id` - delete student

All responses are JSON and use appropriate HTTP status codes.
