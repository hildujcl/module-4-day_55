# Day 55 – Addis Eats API

A backend REST API built with **NestJS and TypeScript** for managing restaurants, dishes, and orders.

## 🛠️ Technologies

- Node.js
- NestJS
- TypeScript
- REST API
- npm

## ✨ Features

- Restaurant management
- Dish management
- Filter dishes by restaurant ID
- Create and retrieve dishes
- Order management
- In-memory repositories
- Dependency injection
- Request validation and error handling

## 📂 Project Structure

```text
addis-eats-api/
├── src/
│   ├── restaurants/
│   ├── dishes/
│   ├── order/
│   ├── app.module.ts
│   └── main.ts
├── package.json
├── package-lock.json
└── tsconfig.json
```

## ⚙️ Installation

Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
```

Navigate into the project:

```bash
cd addis-eats-api
```

Install dependencies:

```bash
npm install
```

## ▶️ Run the Application

Development mode:

```bash
npm run start:dev
```

Build the project:

```bash
npm run build
```

## 🔗 API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/api/restaurants` | Get all restaurants |
| GET | `/api/restaurants/:id` | Get a restaurant |
| GET | `/api/dishes` | Get all dishes |
| GET | `/api/dishes/:id` | Get a dish |
| GET | `/api/dishes?restaurantId=1` | Filter dishes |
| POST | `/api/dishes` | Create a dish |

## 🧪 API Testing

Use the `requests-dishes.http` file to test the dish endpoints.

## 📌 Note

This project uses in-memory repositories for data storage. Data is not permanently stored in a database.

## 👩‍💻 Author

**Hildana Asfaw**

Full Stack Developer
