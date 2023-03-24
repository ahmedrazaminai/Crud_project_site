# Basic CRUD user management system

Made a while ago to learn Golang and Typescript. It's a simple CRUD app that manages users. It has a backend and a frontend. The backend is a REST API built with Golang and Gin. The frontend is a React app, made with Typescript.

## Features
- Master view to list all users
- Form to add new users
- Form to edit existing users
- Button to delete users

## Backend
The backend is a simple REST API built with Golang and Gin. It uses a Sqlite3 database, with Gorm, to store the users.

### API endpoints:
`GET /users` - Get all users<br>
`GET /users/:id` - Get a user by id<br>
`POST /users/` - Create a new user<br>
`PUT /users/:id` - Update a user<br>
`DELETE /users/:id` - Delete a user  

## Frontend
The frontend is a simple React app, made with Typescript. It uses the Bootstrap library for styling.

### Components:
`ActionButtons` - Button that triggers a custom action<br>
`Card` - Card that displays a user's information<br>
`Form` - Form to create or edit a user<br>
`Nav` - Navigation bar<br>
`Alert` - Modal to confirm delete user<br>
`Index` - Main component and master view

