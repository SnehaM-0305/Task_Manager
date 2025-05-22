# Task Manager App

A simple and efficient task management application built with **React**, **Redux Toolkit**, and **TailwindCSS**. This app allows users to manage their tasks with features like adding, editing, deleting, filtering, and marking tasks as completed or pending. Tasks are persisted using **localStorage**.

## Features

- **Add Tasks**: Quickly add new tasks to your list.
- **Edit Tasks**: Modify existing tasks with ease.
- **Delete Tasks**: Remove tasks you no longer need.
- **Mark as Completed**: Toggle tasks between completed and pending states.
- **Search Tasks**: Search for tasks by keywords.
- **Filter Tasks**: Filter tasks by status (All, Completed, Pending).
- **Local Storage**: Tasks are saved in the browser's local storage for persistence.

## Tech Stack

- **React**: For building the user interface.
- **Redux Toolkit**: For state management.
- **TailwindCSS**: For styling.
- **Vite**: For fast development and build tooling.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/task-manager-app.git
   cd task-manager-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open the app in your browser at `http://localhost:5173`.

## Project Structure

```
src/
├── App.css                # Global styles
├── App.jsx                # Main application component
├── assets/                # Static assets
├── components/            # Reusable React components
│   ├── TaskForm.jsx       # Component for adding tasks
│   └── TaskList.jsx       # Component for displaying tasks
├── index.css              # TailwindCSS configuration
├── main.jsx               # Application entry point
├── redux/                 # Redux state management
│   ├── features/          # Redux slices
│   │   └── tasks/
│   │       └── taskSlice.js # Task-related reducers and actions
│   └── store.js           # Redux store configuration
└── vite.config.js         # Vite configuration
```

## Scripts

- `npm run dev`: Start the development server.
- `npm run build`: Build the app for production.
- `npm run preview`: Preview the production build.
- `npm run lint`: Run ESLint to check for code quality.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.

## Acknowledgments

- [React](https://reactjs.org/)
- [Redux Toolkit](https://redux-toolkit.js.org/)
- [TailwindCSS](https://tailwindcss.com/)
- [Vite](https://vitejs.dev/)


Replace `https://github.com/your-username/task-manager-app.git` with the actual repository URL if applicable.
Replace `https://github.com/your-username/task-manager-app.git` with the actual repository URL if applicable.