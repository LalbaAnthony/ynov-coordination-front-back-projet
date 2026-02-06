# 🤝 Contributing Guide

Thanks for your interest in contributing to this project! 🎉

Whether you're fixing a bug, improving documentation, or adding a new feature, your help is very welcome.

## 📋 Table of Contents

- [🤝 Contributing Guide](#-contributing-guide)
  - [📋 Table of Contents](#-table-of-contents)
  - [📜 Code of Conduct](#-code-of-conduct)
  - [❓ How Can I Contribute?](#-how-can-i-contribute)
  - [⚙️ Development Setup](#️-development-setup)
    - [1️⃣ Fork \& Clone](#1️⃣-fork--clone)
    - [2️⃣ Install dependencies](#2️⃣-install-dependencies)
      - [Backend](#backend)
      - [Frontend](#frontend)
    - [3️⃣ Run the project](#3️⃣-run-the-project)
  - [🌱 Branching Strategy](#-branching-strategy)
  - [📝 Commit Message Guidelines](#-commit-message-guidelines)
  - [🔁 Pull Request Process](#-pull-request-process)
    - [Pull Request Checklist](#pull-request-checklist)
  - [💻 Coding Guidelines](#-coding-guidelines)
    - [General](#general)
    - [Frontend (Vue)](#frontend-vue)
    - [Backend (Express)](#backend-express)
  - [🐛 Reporting Bugs](#-reporting-bugs)
  - [💡 Feature Requests](#-feature-requests)
  - [🙏 Thank You](#-thank-you)

## 📜 Code of Conduct

Please be respectful and considerate when interacting with others. Harassment, discrimination, or inappropriate behavior will not be tolerated.

By contributing, you agree to follow basic open‑source etiquette and keep discussions constructive.

## ❓ How Can I Contribute?

You can help in many ways:

* 🐞 Fix bugs
* ✨ Add new features
* 📝 Improve documentation
* 🎨 Improve UI/UX
* 🧪 Add tests
* 🔧 Refactor existing code

## ⚙️ Development Setup

### 1️⃣ Fork & Clone

```bash
git clone https://github.com/your-username/ynov-coordination-front-back-projet.git
cd ynov-coordination-front-back-projet
```

### 2️⃣ Install dependencies

#### Backend

```bash
cd back
npm install
```

#### Frontend

```bash
cd front
npm install
```

### 3️⃣ Run the project

```bash
# Backend
cd back
npm run dev

# Frontend
cd front
npm run dev
```

## 🌱 Branching Strategy

* `main` → stable production branch
* `dev` → active development branch (if applicable)
* `feature/<feature-name>` → new features
* `fix/<bug-name>` → bug fixes

Example:

```bash
git checkout -b feature/add-todo-priority
```

## 📝 Commit Message Guidelines

Please use clear and meaningful commit messages.

Recommended format:

```
<type>: <short description>
```

Examples:

* `feat: add todo completion filter`
* `fix: resolve API crash on empty payload`
* `docs: update README installation steps`
* `refactor: simplify todo controller logic`

Common types:

* `feat`
* `fix`
* `docs`
* `style`
* `refactor`
* `test`
* `chore`

## 🔁 Pull Request Process

1. Make sure your branch is up to date with `main`
2. Ensure the project builds and runs correctly
3. Write clear commit messages
4. Open a Pull Request with:

   * What you changed
   * Why you changed it
   * Any related issues

### Pull Request Checklist

* [ ] Code builds without errors
* [ ] No linting issues
* [ ] Changes are documented if necessary
* [ ] No breaking changes (or clearly explained)

## 💻 Coding Guidelines

### General

* Use **TypeScript** consistently
* Prefer readable and maintainable code over clever hacks
* Keep functions small and focused

### Frontend (Vue)

* Use Composition API when possible
* Keep components small and reusable
* Avoid business logic inside templates

### Backend (Express)

* Follow REST conventions
* Validate request data
* Handle errors properly (no silent failures)

## 🐛 Reporting Bugs

When reporting a bug, please include:

* Steps to reproduce
* Expected behavior
* Actual behavior
* Screenshots or logs if available

Open an issue with the label **bug**.

## 💡 Feature Requests

Feature ideas are welcome!

Please include:

* Problem description
* Proposed solution
* Any alternatives considered

Open an issue with the label **enhancement**.

## 🙏 Thank You

Every contribution matters ❤️

Thank you for helping improve this project!
