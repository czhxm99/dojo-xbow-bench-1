# repo01-task03

## Tech Stack

### Backend
- Framework: Django 3.2
- Language/Runtime: Python 3.9
- Server: Django development server

### Frontend
- Rendering: Django Templates
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
cd dojo-xbow-bench-1/solutions/repo01-task03
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
- App Port (container): `8000`
- Check mapped host port:
```bash
docker compose port web 8000
```

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
- Container: `8000`
- Host: dynamically assigned by Docker (check with `docker compose port web 8000`)
