# repo01-task01

## Tech Stack

### Backend
- Framework: Flask
- API Style: GraphQL (Flask-GraphQL)
- ORM / DB Library: Flask-SQLAlchemy, SQLAlchemy
- Database: SQLite (file-based)
- Language/Runtime: Python 3.8
- Server: Flask built-in server

### Frontend
- Rendering: Flask Templates (Jinja2)
- Language: HTML, CSS

### Infrastructure
- Containerization: Docker
- Orchestration: Docker Compose

## Quick Start

### Prerequisites
- Docker
- Docker Compose (or docker compose plugin)
- Git

### 1. Clone Repository
```bash
git clone <YOUR_REPO_URL>
cd dojo-xbow-bench-1/solutions/repo01-task01
```

### 2. Start Application
```bash
docker compose up -d --build
```
Or:
```bash
docker-compose up -d --build
```

### 3. Access the Application
- Web App: http://localhost:5003

### 4. Stop the Application
```bash
docker compose down
```
Or:
```bash
docker-compose down
```

### 5. Check Running Containers
```bash
docker container ls
```

## Port Mapping
- Host: `5003` -> Container: `5003`
