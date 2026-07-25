# TypeScript Hello World Webpage

A clean, minimal TypeScript starter project that shows how to render a simple greeting in the browser using a basic HTML + JavaScript workflow.

<p align="center">
  <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer">
    <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white&style=for-the-badge" />
  </a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank" rel="noreferrer">
    <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white&style=for-the-badge" />
  </a>
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer">
    <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black&style=for-the-badge" />
  </a>
</p>

## ✨ Overview

This repository is a tiny, beginner-friendly example of the classic TypeScript-to-browser workflow. It demonstrates how to:

- write application logic in TypeScript
- compile that TypeScript into JavaScript
- load the compiled script from an HTML page

The codebase is intentionally lightweight, making it a great starting point for learning, experimenting, and building simple frontend prototypes.

## 🧱 Project Structure

```text
.
├── app.ts        # TypeScript source
├── app.js        # Compiled JavaScript output
├── index.html    # Browser entry point
└── README.md     # Project documentation
```

## 🚀 Getting Started

### Option 1: Open directly

Open `index.html` in your browser.

### Option 2: Serve locally

```bash
python3 -m http.server 8000
```

Then browse to:

```text
http://localhost:8000
```

## 🔧 Compile TypeScript

If you want to regenerate the JavaScript from the TypeScript source, run:

```bash
npx tsc app.ts
```

This updates `app.js`.

## 🧠 How It Works

1. `app.ts` holds the TypeScript logic.
2. The TypeScript compiler transpiles that file into `app.js`.
3. `index.html` loads the JavaScript file, and the browser renders the message.

## ✅ Why This Project Exists

This repo is designed to provide the simplest possible example of a TypeScript-driven webpage. It avoids unnecessary tooling so the core learning path stays clear.

## 📌 Notes

- No framework
- No package installation required for the basic demo
- No build pipeline complexity

This makes the repository ideal for first-time TypeScript learners or anyone who wants a tiny, dependable reference implementation.

## 📄 License

This project is provided for educational and demonstration purposes.