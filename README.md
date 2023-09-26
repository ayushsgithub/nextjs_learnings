 # Redux Todo App

This is a simple todo app built with the help of React, Vite, Tailwind and Redux. This README aims to provide an overview of the app and how to get it up and running.

![todo png](https://github.com/ayushsgithub/redux_Todo/blob/main/src/assets/todo.png?raw=true)

## Getting Started

To get the app running locally:

1. Clone the repository:

```
git clone https://github.com/ayushsgithub/redux_Todo.git
```

2. Install dependencies: 

```
npm install
```

3. Start the development server:

```
npm start
```

The app will be served at `http://localhost:3000`.

4. Add todos by typing in the input box and clicking the "Add Todo" button.


5. Delete todos by clicking the "BIN" button.

## App Structure

The app consists of the following components:

`AddTodo.jsx`: Contains the input box and "Add Todo" button. On submit, dispatches an action to add a todo.

`Todos.jsx`: Lists all todos. Contains each todo and a "BIN" button to delete. Dispatches actions accordingly.

`store.js`: Redux store configuration.

`index.js`: Main app component that renders the TodoInput and TodoList components.

## Technologies Used

- React - For the UI
- Redux - For state management 
- Tailwind - For CSS

## Improving the App

Some things that could be improved:

- Add filtering/sorting of todos 
- Add editing of existing todos

# React + Vite


This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh