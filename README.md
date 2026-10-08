# golang-todo-list-app

A simple, lightweight web server written in Go designed to handle incoming HTTP client requests. 
This project serves as a clean baseline and demo for Go-based HTTP services.

## Usage & API Endpoints
The server is listening on port `:8080`
| Method | Endpoint | Description
| ------------- | ------------- | ------------- |
GET | `/` | Greets the user (`helloUser` handler) |
GET | `/show-tasks` | Displays task list (`showTasks` handler) |
