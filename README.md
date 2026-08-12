\# Task API



A simple CRUD API for managing a to-do list, built with FastAPI. Tasks are stored in memory (no database) — data resets when the server restarts.



\## How to run



1\. Install dependencies:

2\. Start the server:

3\. Visit `http://localhost:8000/docs` for interactive API docs.



\## Endpoints



| Method | Path | Description |

|--------|------|-------------|

| GET | / | API info |

| GET | /health | Health check |

| GET | /tasks | List all tasks |

| GET | /tasks/{id} | Get one task |

| POST | /tasks | Create a task |

| PUT | /tasks/{id} | Update a task |

| DELETE | /tasks/{id} | Delete a task |



\## Example request

Response:

\## Swagger UI



Screenshot of `/docs` showing all endpoints:



!\[Swagger UI](swagger-screenshot.png)

