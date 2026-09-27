# Student Management REST API

Web Dev III - Lab Assignment 2

## Requirements
- Node.js
- Express.js
- Postman
- No database
- Array/JSON data only

## Setup

Open the project folder in VS Code terminal:

```bash
npm install
node app.js
```

The server will run at:

http://localhost:3000

## API Endpoints

| Method | URL | Purpose |
|---|---|---|
| GET | /students | Get all students |
| GET | /students/:id | Get one student |
| POST | /students | Add student |
| PUT | /students/:id | Update student |
| DELETE | /students/:id | Delete student |

## POST body

```json
{
  "name": "Neha Gupta",
  "age": 20,
  "course": "B.Tech CSE"
}
```

## PUT body

```json
{
  "name": "Neha Gupta Updated",
  "age": 21,
  "course": "B.Tech CSE"
}
```

## Status Codes
- 200 Success
- 201 Created
- 400 Bad Request
- 404 Not Found
- 500 Internal Server Error
