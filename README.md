# REST API with Node.js, Express, and MongoDB

A simple REST API for managing users with CRUD operations.

## Setup

1. Clone the repository:
```bash
git clone https://github.com/SeifKar/REST_API.git
cd REST_API
```

2. Install dependencies:
```bash
npm install
```

3. Create a `config/.env` file with the following content:
```env
MONGO_URI=mongodb://localhost:27017/userDB
PORT=3000
```

4. Start the server:
```bash
node server.js
```

## API Endpoints

- GET `/api/users` - Get all users
- POST `/api/users` - Create a new user
- PUT `/api/users/:id` - Update a user by ID
- DELETE `/api/users/:id` - Delete a user by ID

## Example User Object
```json
{
    "name": "John Doe",
    "email": "john@example.com",
    "age": 30
}
```
