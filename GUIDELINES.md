# 📌 Project Guidelines

These guidelines define **how this project should be written, structured, and maintained**. They are here to keep the codebase clean, consistent, and easy to work with for everyone.

This document complements `README.md` and `CONTRIBUTING.md`.

---

## 🎯 Project Goals

* Keep the codebase **simple and readable**
* Maintain **clear separation** between frontend and backend
* Favor **maintainability over premature optimization**
* Use **TypeScript effectively**, not just as JavaScript with types

---

## 📁 Repository Structure

```
root/
├── front/          # Vue.js (TypeScript) frontend
├── back/           # Express.js (TypeScript) backend
├── README.md
├── CONTRIBUTING.md
├── GUIDELINES.md
```

Each folder should remain **self‑contained**.

---

## 🧱 General Coding Rules

* Use **TypeScript everywhere**
* Avoid `any` unless absolutely necessary
* Prefer explicit types for public APIs and function boundaries
* Keep files small and focused
* One responsibility per module

---

## 🖥️ Frontend Guidelines (Vue + TypeScript)

### Structure

* Use the **Composition API**
* One main component per file
* Reusable logic should live in `composables/`
* Global state should be handled via a store (Pinia, if used)

### Components

* Keep templates clean and readable
* Avoid heavy logic inside templates
* Use props & emits explicitly
* Name components using **PascalCase**

### Styling

* Prefer utility‑first CSS (Tailwind) or scoped styles
* Avoid global styles unless necessary
* Keep styling consistent across components

---

## 🔌 Backend Guidelines (Express + TypeScript)

### Structure

* Separate concerns:

  * `routes` → HTTP layer
  * `controllers` → request handling
  * `services` → business logic
  * `models` → data structures

### API Design

* Follow REST conventions
* Use meaningful HTTP status codes
* Validate request input
* Never trust client data

### Error Handling

* Centralize error handling
* Never expose stack traces in production
* Use clear and consistent error messages

---

## 🔐 Environment & Configuration

* All secrets must live in `.env` files
* Never commit `.env` files
* Provide `.env.example` when possible

---

## 🧪 Testing Guidelines

* Write tests for critical logic when applicable
* Prefer small, isolated tests
* Avoid testing implementation details

Testing is encouraged but not mandatory unless stated.

---

## 🧹 Code Quality

* Remove unused code and imports
* Avoid commented‑out code
* Refactor when duplication appears
* Keep naming consistent and meaningful

---

## 🔁 Version Control Rules

* Keep commits small and focused
* One logical change per commit
* Do not commit broken builds

---

## 🚫 What to Avoid

* Over‑engineering
* Deeply nested logic
* Large components or controllers
* Silent error handling

---

## 🗣️ Communication

* Be respectful in discussions and reviews
* Explain *why* a change is made, not just *what*
* Ask questions when unsure

## ✅ Final Notes

These guidelines are meant to help, not slow you down.

If a rule does not make sense in a specific case, use good judgment and document your reasoning.

Happy coding 🚀
