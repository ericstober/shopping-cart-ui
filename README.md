# Shopping Cart UI

A simple shopping cart user interface built with **Vite**, **React**, and **Tailwind CSS**.
The primary purpose of this project is to demonstrate the use of **React’s Context API** for global state management.

## Features

- Product listing UI
- Add/remove items from the cart
- Update item quantities
- Global cart state managed with React Context
- Responsive styling with Tailwind CSS
- Fast development setup using Vite
- Persistant cart state using localStorage

## Learning Focus

This project was created to showcase:

- How to create and provide context using `React.createContext`
- Managing shared state across components without prop drilling
- Structuring a React app around context-based state management

## Tech Stack

- **Vite** – Fast build tool and dev server
- **React** – UI library
- **Tailwind CSS** – Utility-first CSS framework
- **Context API** – State management

## Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/ericstober/shopping-cart-ui.git
cd shopping-cart-ui
npm install
```

## Running the App

Start the development server:

```bash
npm run dev
```

Then open your browser at:
`http://localhost:5173`

## Project Structure (Simplified)

src/
├── components/ # UI components
├── context/ # Cart context and provider
├── pages/ # Page-level components
├── App.jsx
└── main.jsx
