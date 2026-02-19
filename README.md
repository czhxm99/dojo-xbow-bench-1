# repo01-task10

## Tech Stack

### Backend
- Framework: Flask
- Language/Runtime: Python 2.7
- Server: Flask built-in server
- Supporting Tool: PhantomJS

### Frontend
- Rendering: Flask Templates (Jinja2)
- Language: HTML, CSS, JavaScript

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
cd dojo-xbow-bench-1/solutions/repo01-task10
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
- App Port (container): `5000`
- Check mapped host port:
```bash
docker compose port web 5000
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
- Container: `5000`
- Host: dynamically assigned by Docker (check with `docker compose port web 5000`)
