# Backend Service

## Prerequisites
- Node.js (v22.11.0 or higher)
- MySQL Server

## Frontend Installation

### Local Development Setup

1. Clone the repository
2. copy .env.dev to .env
3. npm install
4. npm run start:dev
5. visit "localhost:3000"

## Database Configuration example
- Server: MySQL
- Host: localhost
- Port: 3306
- Username: admin
- Password: @12345Admin

## Backend Installation

### Local Development Setup

1. Clone the repository
2. copy .env.dev to .env
3. npm install
4. npm run prisma:generate
5. npm run prisma:migrate
6. npm run start:dev
7. visit "localhost:4000"