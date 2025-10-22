# Task Organizer Microservice

## Overview
This microservice provides a REST API for managing tasks. It allows users to retrieve, add, and delete tasks through simple HTTP endpoints.

## Endpoints

### GET /tasks
Returns a list of all tasks.

### GET /task/{taskname}
Returns a specific task by name.

### DELETE /task/{taskname}
Deletes a specific task by name.

### POST /task
Adds a new task to the list.

## Swagger Configuration
The service includes a swagger configuration file (`swagger_config.json`) that defines the API specifications and endpoints.

## Running the Service
To run this microservice, execute:

```bash
python app.py
```

The service will be available at `http://localhost:5000`.

## Dependencies
- Flask
- Flask-CORS
- Werkzeug