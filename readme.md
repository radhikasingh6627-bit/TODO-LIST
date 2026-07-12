# ✅ To-Do List

A minimal, interactive to-do list web app built with plain HTML, CSS and JavaScript. Add tasks, mark them complete with a single click, and remove them with a double click.

Made by **Radhika Singh** as part of my personal JavaScript/DOM practice projects.

## 🔗 Live Demo

> Add your live demo link here after deploying (e.g. via GitHub Pages) — see the "Deploying with GitHub Pages" section below.

## 📸 Preview

> Add a screenshot of the app here after uploading, e.g.:
> `![To-Do List preview](preview.png)`

## ✨ Features

- Add new tasks via a text input and "Add" button
- **Single click** on a task → marks it complete (strikethrough)
- **Double click** on a task → removes it from the list
- Input field automatically clears after adding a task

## 🛠️ Tech Stack

- **HTML5** – page structure
- **CSS3** – styling and layout
- **JavaScript (ES6)** – dynamic DOM element creation, update and removal

## 📁 Project Structure

```
todo-list/
├── index.html      # Structure, styles, and logic (single file)
└── README.md        # This file
```

## 🚀 How to Run Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/todo-list.git
   cd todo-list
   ```
2. Open `index.html` directly in any modern web browser (double-click it, or right-click → Open with → Chrome/Edge).

No build step, no dependencies, no server required.

## 🧠 How It Works

- Clicking **Add** creates a new `<p>` element via `document.createElement("p")` with the input's text and appends it to the list using `appendChild`.
- A `click` listener on each task toggles `textDecoration: line-through` to mark it complete.
- A `dblclick` listener on each task calls `removeChild` to delete it from the DOM.

## 🔮 Future Enhancements

- Persist tasks using the browser's `localStorage` so they survive a page refresh
- Add due dates / priority levels
- Add a "Clear completed" button

## 👩‍💻 Author

**Radhika Singh**
B.Tech CSE (AI & ML), Shri Ramswaroop Memorial University

## 📄 License

This project is open source and available under the MIT License.
