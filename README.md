# Zenvofin's devops

## Requirements

- Docker
- Docker Compose
- Docker Desktop

## Installation process

1. Clone this repository to your local machine.
2. Run the Docker Compose stack: `docker compose up -d` (or `docker compose up -d --build` to rebuild images).
3. Navigate to Seq (http://localhost:5341).
4. Login with admin / admin, change the password, and generate an API key for the Back-End by:
   - Opening the Seq Settings page.
   - Navigating to the **API keys** section.
   - Creating a new API key for the back-end service.
   - Copying the generated key and configuring your Back-End to use it for authenticating with Seq.