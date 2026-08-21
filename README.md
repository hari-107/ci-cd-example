# CI/CD Example

A small Flask application used to demonstrate a CI/CD workflow with GitHub, Jenkins, automated tests, and Docker.

## Pages

- `/` — project landing page
- `/pipeline` — CI/CD pipeline stages
- `/about` — project architecture and technology overview
- `/health` — JSON health check

## Flow

`Developer → GitHub → Jenkins → Test → Docker Build → Deployment`

Run locally with `python app.py` and open `http://localhost:5000`.
