## Repositories
- [Frontend Repository](https://github.com/AymanNagyAhmed/chemist-task-frontend)
- [Backend Repository](https://github.com/AymanNagyAhmed/chemist-task-backend)
- [Install using docker](https://github.com/AymanNagyAhmed/chemist-task)
- [Postman Collection](https://github.com/AymanNagyAhmed/chemist-task-backend/blob/main/Chemist-Warehouses-task.postman_collection.json)

## Prerequisites
- Docker & docker-compose

## Installation using Docker

```
task
├── docker-compose.yml
├── backend
│   └── Dockerfile.dev
└── frontend
    └── Dockerfile.dev
```

Required files:
- docker-compose.yml ([download](https://github.com/AymanNagyAhmed/chemist-task/blob/main/docker-compose.yml))
- backend/Dockerfile.dev ([download](https://github.com/AymanNagyAhmed/chemist-task-backend/blob/main/Dockerfile))
- frontend/Dockerfile.dev ([download](https://github.com/AymanNagyAhmed/chemist-task-frontend/blob/main/Dockerfile))

Steps:
1. Make sure you follow the correct folder structure
2. Make sure you copied .env.dev to .env
3. Run this command:
```bash
docker-compose up -d --build
```

### PhpMyAdmin
```
URL: http://localhost:8080
Server: mysql
Username: admin
Password: @12345Admin
```

### Backend
- API URL: http://localhost:4000/api
- [Postman Collection](https://github.com/AymanNagyAhmed/chemist-task-backend/blob/main/Chemist-Warehouses-task.postman_collection.json)

### Frontend
```
http://localhost:3000
```