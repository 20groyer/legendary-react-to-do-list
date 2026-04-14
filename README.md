# React To-Do List

A simple, interactive to-do list built with React and Vite — featuring task creation, deletion, and up/down reordering.

---

## The Story Behind It

People have their different approaches to learning new languages, and mine has changed from time to time.

This all began when I joined a pretty cool team and wanted to build something to match. I'd argue that the legendary to-do list is one of the best beginner projects out there — it covers everything from basic `if` statements to simple delete functions, and forces you to actually think in the framework you're trying to learn.

I wanted to build something with a modern, relevant stack that could be adaptable for engineers to come — so I chose React. The only thing was, I didn't know a thing about React. But that was exactly the point. The unfamiliarity wasn't a barrier; it was the invitation.

I started by reading the documentation to get the basic gist of it, then picked this small project to implement the "little" that I understood. I found a great YouTube tutorial to guide the build, and as I was putting the pieces together, the simplicity of it all just began to fall into place.

It's one thing to read documentation and understand the theory of how things work. It's another — and I'd argue a better — step to actually implement it and still understand *why* as you go.

This was my own little introduction to React. I hope you enjoy it, and that it inspires you too. 🚀

---

## Features

- Add tasks via text input
- Delete tasks individually
- Reorder tasks up or down
- Clean, minimal UI

---

## Tech Stack

- **React 19** — UI and state management via `useState`
- **Vite** — fast dev server and build tool
- **JavaScript (JSX)** — component-based structure

---

## Project Structure

```
src/
├── ToDoList.jsx    # Core component — all task logic lives here
├── App.jsx         # Root component
├── main.jsx        # Vite entry point
└── index.css       # Global styles
```

---

## Getting Started

**Prerequisites:** Node.js installed

```bash
# Clone the repo
git clone https://github.com/your-username/your-repo-name.git

# Navigate into the project
cd todo-list-app

# Install dependencies
npm install

# Run the dev server
npm run dev
```

Then open [http://localhost:5173](http://localhost:5173) in your browser.

---

## What I Learned

- How React's `useState` hook manages and updates state
- Controlled components — binding input values to state
- Array methods like `.filter()` and spread syntax for immutable state updates
- Destructuring assignment for swapping array elements (used in the move up/down logic)
- The difference between reading about a framework and actually building with it

---

## License

Free to use for learning and inspiration.