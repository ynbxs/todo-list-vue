# 🗒️ Todo List (Vue.js)

A simple and responsive **Todo List** built with **Vue.js 3** and **Bootstrap 5**.  
Easily **add**, **mark as completed**, **delete**, and visually **highlight** your tasks.

## 🚀 Live Demo
[View it on GitHub Pages](https://ynbxs.github.io/todo-list-vue/) 

## 🔧 Features
- ➕ Add new tasks
- ✅ Mark tasks as done
- ❌ Remove tasks from the list
- 🌟 Highlight completed tasks for easy visual tracking
- 🎨 Styled with Bootstrap 5

## 🧠 Concept
This Todo List is designed as a **lightweight component** to help users manage their daily tasks with ease. It uses Vue’s core features (`v-model`, `v-for`, and event binding) to create a reactive and interactive experience.

## 🧩 Structure
- `index.html` – App container & Vue bindings
- `style.css` – Custom styles for task highlights and layout
- `script.js` – Vue.js app logic (task list, add/delete/toggle)
- `README.md` – Project documentation

## 💡 How it Works
- Tasks are listed using `v-for` to loop through the `todos` array.
- Each task has:
  - A **checkbox** bound to `todo.done` (via `v-model`) to toggle completion.
  - A **delete** button to remove the task from the list.
- Completed tasks are styled with a green background and white text using dynamic class binding.

## 📦 Technologies
- [Vue.js 3 (via CDN)](https://vuejs.org/)
- [Bootstrap 5](https://getbootstrap.com/)
- [Font Awesome](https://fontawesome.com/)
- HTML5 & JavaScript (ES6)

## 📌 Ideas for Future Improvements
- Persistent storage using LocalStorage
- Task editing feature
- Drag-and-drop sorting
- Category or tag filters

---
