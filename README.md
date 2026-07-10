# Prisma ORM Practice

A beginner-friendly Prisma ORM project demonstrating how to connect a PostgreSQL database, define models, run migrations, and perform CRUD operations using Prisma Client with Node.js and TypeScript.

## 🚀 Features

* Prisma ORM setup
* PostgreSQL database integration
* Prisma Schema modeling
* Database migrations
* Prisma Client generation
* CRUD operations (Create, Read, Update, Delete)
* Type-safe database queries
* Clean project structure

## 🛠️ Tech Stack

* Node.js
* TypeScript
* Prisma ORM
* PostgreSQL
* Express.js

## 📂 Project Structure

```text
├── prisma/
│   ├── schema.prisma
│   └── migrations/
├── src/
│   ├── app.ts
│   ├── server.ts
│   └── modules/
├── .env
├── package.json
└── README.md
```

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/your-username/prisma-practice.git
```

### Navigate to the project

```bash
cd prisma-practice
```

### Install dependencies

```bash
npm install
```

### Configure environment variables

Create a `.env` file and add:

```env
DATABASE_URL="postgresql://username:password@localhost:5432/database_name"
```

### Generate Prisma Client

```bash
npx prisma generate
```

### Run database migrations

```bash
npx prisma migrate dev --name init
```

### Start the development server

```bash
npm run dev
```

## 📖 Useful Prisma Commands

```bash
# Initialize Prisma
npx prisma init

# Generate Prisma Client
npx prisma generate

# Create Migration
npx prisma migrate dev --name migration_name

# Open Prisma Studio
npx prisma studio

# Push Schema to Database
npx prisma db push

# Pull Existing Database Schema
npx prisma db pull

# Reset Database
npx prisma migrate reset
```

## 📚 What I Learned

* Setting up Prisma ORM
* Designing database schemas
* Creating and applying migrations
* Working with Prisma Client
* Performing CRUD operations
* Managing relationships between models
* Writing type-safe database queries

## 📄 License

This project is open-source and available under the MIT License.
