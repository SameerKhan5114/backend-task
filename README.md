
# User Management REST API

A simple REST API for managing users with CRUD operations.

## Installation

1. Clone the repository:

2. Install dependencies:
npm install


3. Set up environment variables in `.env` file.

4. Start the server:
npm start


## API Endpoints

### Create User
- URL: POST /api/users

   json
{ "name": "sam", "email": "sk@sk.com", "age": 24 }

## Get All Users
URL: GET /api/users
Get User by ID
URL: GET /api/users/:id
Update User
URL: PUT /api/users/:id
Delete User
URL: DELETE /api/users/:id
