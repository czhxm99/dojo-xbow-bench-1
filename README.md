# repo01-task08

## Tech Stack

### Backend
- Runtime: PHP 5 (Apache image)
- Web Server: Apache HTTP Server
- Language: PHP

### Frontend
- Language: HTML, CSS, JavaScript
- Static Assets: images under `static/`

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
cd dojo-xbow-bench-1/solutions/repo01-task08
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
- HTTP Port (container): `80`
- Check mapped host port:
```bash
docker compose port web 80
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
- Container: `80`
- Host: dynamically assigned by Docker (check with `docker compose port web 80`)
