# Task Manager App

## Overview
A simple task management application with user authentication, task categorization, due dates, and real-time updates using ActionCable.

## Tech Stack
- **Backend**: Ruby on Rails (API mode)
- **Frontend**: React
- **Database**: PostgreSQL
- **Real-time Updates**: ActionCable (WebSockets)

## Features
- User authentication (signup, login, logout)
- CRUD operations for tasks
- Categorization of tasks
- Due dates and reminders
- Real-time task updates

## Installation

### Backend (Rails API)
1. Clone the repository:
   ```sh
   git clone https://github.com/anjadriano16/task-manager-api.git
   cd task-manager-api
   ```
2. Install dependencies:
   ```sh
   bundle install
   ```
3. Set up the database:
   ```sh
   rails db:create db:migrate
   ```
4. Start the Rails server:
   ```sh
   rails s
   ```

### Frontend (React)
1. Navigate to the frontend directory:
   ```sh
   cd ../task-manager-frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the React development server:
   ```sh
   npm start
   ```

## API Endpoints
| Method | Endpoint | Description |
|--------|---------|-------------|
| POST | /signup | Register a new user |
| POST | /login | Authenticate user |
| GET | /tasks | Retrieve all tasks |
| POST | /tasks | Create a new task |
| PUT | /tasks/:id | Update a task |
| DELETE | /tasks/:id | Delete a task |

## License
This project is licensed under the MIT License.

