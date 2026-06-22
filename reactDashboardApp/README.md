# Task Dashboard

A React and TypeScript task management dashboard built with Vite. The app lets users review task metrics, search and filter tasks, add new tasks, update task status, delete tasks, and inspect due dates on a calendar.

## Features

- Dashboard metrics for total, completed, in-progress, overdue, and high-priority tasks
- Task search by title
- Filtering by status and priority
- Task creation, deletion, and status updates
- Calendar view with due-date markers and selected-date agenda
- Local persistence with `localStorage`
- Responsive dashboard layout

## Tech Stack

- React
- TypeScript
- Vite
- Bootstrap utility classes and Bootstrap Icons from CDN
- React Calendar

## Project Structure

```text
src/
├── components/
│   ├── Dashboard/
│   ├── TaskFilter/
│   ├── TaskForm/
│   └── TaskList/
├── data/
├── types/
├── App.tsx
├── App.css
├── index.css
└── main.tsx
```

## Setup

```bash
npm install
npm run dev
```

## Scripts

- `npm run dev` starts the Vite development server.
- `npm run build` runs TypeScript checks and creates a production build.
- `npm run lint` runs ESLint.
- `npm run preview` previews the production build locally.
