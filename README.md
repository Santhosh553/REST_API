# Full Stack REST API Application

## Overview

This is a full-stack web application built using modern technologies. It includes a REST API and a frontend UI.

## Technologies Used

- **Frontend**: Next.js 14 (TypeScript), Tailwind CSS
- **Backend**: Node.js, Express (JavaScript)
- **Database**: PostgreSQL, Prisma
- **Containerization**: Docker, Docker Compose

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/yourprojectname.git
   cd yourprojectname

2. **Install Dependencies**:
   ```bash
   npm install

3. **Environment Variables: Create a .env file with your database connection string**.
   ```bash
   DATABASE_URL="postgresql://username:password@localhost:5432/yourdatabase"

4. **Setup Prisma**:
   Generate the Prisma client
   ```bash
   npx prisma generate

6. **Start the Application**:
   **Using Docker**:
   ```bash
   docker-compose up --build
   ```
   **Locally**:
   ```bash
   cd backend
   node index.js

   cd frontend
   npm run dev


   
