# 📝 TodoList Project

A full‑stack **TodoList application** built with a **Vue.js (TypeScript)** frontend and a **Node.js Express (TypeScript)** backend. The project is split into two main folders: `front` and `back`, making it easy to develop and scale both sides independently.

## 📁 Project Structure

```
root/
├── front/          # Vue.js + TypeScript frontend
├── back/           # Express.js + TypeScript backend
├── README.md
```

## 🚀 Features

* Create, update, delete todos
* Mark todos as completed
* RESTful API
* TypeScript on both frontend and backend
* Clear separation between client and server

## 🧰 Tech Stack

### Frontend (`front`)

* Vue.js
* TypeScript
* Vite (or Vue CLI, depending on your setup)
* Axios / Fetch API
* Tailwind CSS or CSS (if applicable)

### Backend (`back`)

* Node.js
* Express.js
* TypeScript
* REST API
* (Optional) Database: JSON / SQLite / MongoDB / PostgreSQL

## ⚙️ Prerequisites

Make sure you have the following installed:

* Node.js >= 18
* npm or yarn

## 🔧 Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/ynov-coordination-front-back-projet.git
cd ynov-coordination-front-back-projet
```

### 2️⃣ Backend setup (`back`)

```bash
cd back
npm install
```

#### Environment variables

Create a `.env` file in the `back` folder:

```env
PORT=3000
```

#### Run the backend

```bash
npm run dev
```

The backend will start on:

```
http://localhost:3000
```

### 3️⃣ Frontend setup (`front`)

```bash
cd front
npm install
```

#### Environment variables

Create a `.env` file in the `front` folder:

```env
VITE_API_URL=http://localhost:3000
```

#### Run the frontend

```bash
npm run dev
```

The app will be available at:

```
http://localhost:5173
```

## 🔁 API Overview

### Base URL

```
http://localhost:3000/api
```

### Endpoints (example)

| Method | Endpoint   | Description       |
| ------ | ---------- | ----------------- |
| GET    | /todos     | Get all todos     |
| POST   | /todos     | Create a new todo |
| PUT    | /todos/:id | Update a todo     |
| DELETE | /todos/:id | Delete a todo     |

## 🧪 Scripts

### Backend

```bash
npm run dev      # Start in development mode
npm run build    # Build TypeScript
npm run start    # Start production server
```

### Frontend

```bash
npm run dev      # Start dev server
npm run build    # Build for production
npm run preview  # Preview production build
```

## 📦 Build for Production

### Backend

```bash
cd back
npm run build
npm run start
```

### Frontend

```bash
cd front
npm run build
```

The production files will be generated in the `dist/` folder.

## 🔐 CORS & Security Notes

* Ensure CORS is enabled on the backend for the frontend URL
* Never commit `.env` files
* Use environment variables for secrets

## 🛠️ Future Improvements

* Authentication (JWT)
* Database persistence
* User accounts
* Filters & search
* Docker support

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a feature branch
3. Commit your changes
4. Open a pull request

## 📄 License

This project is licensed under the MIT License.

## ✨ Author

Built with ❤️ using Vue.js and Express.
