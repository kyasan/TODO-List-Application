# Todo List Application

A clean and beautiful Todo List web application built with React + TypeScript.

<img width="1241" alt="截屏2025-04-25 20 27 03" src="https://github.com/user-attachments/assets/732b169e-4cdb-4073-b84c-e440f567656d" />

## Features

- Clean and minimalist user interface
- Add new todo items
- Mark todos as complete/incomplete
- Delete todo items
- Filter by status: All/Active/Completed
- Display creation date for each todo
- Auto-save to local storage, data persists after page refresh

## Tech Stack

- React 18
- TypeScript
- CSS3 (Theme management using CSS variables)
- LocalStorage (Data persistence)

## Getting Started

1. Clone the repository
```bash
git clone https://github.com/kyasan/TODO-List-Application.git
cd todo-list
```

2. Install dependencies
```bash
npm install
```

3. Start development server
```bash
npm run dev
```

4. Open in browser
```
http://localhost:5173
```

## Project Structure

```
src/
├── types/          # TypeScript type definitions
│   └── Todo.ts     # Todo interface definition
├── App.tsx         # Main application component
├── App.css         # Application styles
├── main.tsx        # Application entry point
└── index.css       # Global styles
```

## How to Use

1. Enter todo content in the input field, press Enter or click "Add" button to add
2. Click the checkbox next to a todo item to toggle its completion status
3. Click the "×" button on the right to delete a todo item
4. Use "All", "Active", "Completed" buttons to filter todos by status
5. All operations are automatically saved to browser's local storage
