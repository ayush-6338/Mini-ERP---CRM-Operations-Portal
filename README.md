# Mini-ERP---CRM-Operations-Portal
project for me to understand all the tool of fullstack

ok, I am starting my setup instruction from here onwards:

## 🚀 Setup Instructions

This project includes a Node.js/Express backend, a React frontend, and a PostgreSQL database. You can run this project locally using Docker (recommended) or via standard local installation.

### Prerequisites
- [Docker & Docker Compose](https://www.docker.com/) (Recommended)
- [Node.js](https://nodejs.org/) (v18+ if running manually)
- [PostgreSQL](https://www.postgresql.org/) (if running manually)

### 🔐 Environment Variables

You must manage and configure your environment variables before running the application. Create a `.env` file in the root of both the `backend` and `frontend` directories based on the examples below.

**Backend (`backend/.env`):**
```env
PORT=3000
DATABASE_URL=postgresql://user:password@localhost:5432/minierp
JWT_SECRET=your_super_secret_jwt_key