# Login Auth API (NestJS)

This project is a backend API for user authentication, built using NestJS and TypeScript. It implements secure login and registration features using JWT (JSON Web Tokens) and follows best practices for modular code organization.

## 📁 Project Structure

```
login-auth_nestjs/
├── src/
│   ├── auth/
│   ├── users/
│   ├── common/
│   ├── app.module.ts
│   └── main.ts
├── .env
├── package.json
├── tsconfig.json
└── README.md
```

## 🚀 Technologies Used

- **Node.js**: JavaScript runtime
- **NestJS**: Progressive Node.js framework for building efficient and scalable server-side applications
- **TypeScript**: Typed superset of JavaScript
- **JWT**: JSON Web Token for secure user authentication
- **bcrypt**: For hashing user passwords
- **PostgreSQL** (or other relational databases via TypeORM)
- **TypeORM**: ORM for TypeScript and JavaScript

## 🔐 Features

- User registration and login
- Password hashing with bcrypt
- JWT-based authentication
- Role-based access control
- Modular and scalable architecture

## 🔧 Getting Started

1. **Clone the repository:**

```bash
git clone https://github.com/FabricioHiury/login-auth_nestjs.git
cd login-auth_nestjs
```

2. **Install dependencies:**

```bash
npm install
```

3. **Configure environment variables (.env):**

```
JWT_SECRET=your_jwt_secret_key
DATABASE_URL=your_database_connection_string
```

4. **Run the development server:**

```bash
npm run start:dev
```
