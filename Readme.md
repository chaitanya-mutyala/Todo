# React Todo App

A simple and interactive **Todo application** built with **React**. This app allows users to add, edit, complete, and delete, dynamically reorder todos . It uses **localStorage** to persist data, so todos are not lost on page reload.

---

## Features

- ✅ Add new todos  
- ✅ Edit existing todos  
- ✅ Mark todos as completed  
- ✅ Delete todos  
- ✅ Persistent storage using `localStorage`  
- ✅ Dynamically Reorder todos
- ✅ Responsive and user-friendly UI  
- ✅ Styled with Tailwind CSS  

---

## Demo

🔗 **Live Demo:** [Currency Converter](https://todo-liart-seven-15.vercel.app/)
---

## Installation

1. **Clone the repository:**

```bash
git clone https://github.com/chaitanya-mutyala/Todo.git
cd Todo
```

2. **Install dependencies:**

```bash
npm install
```

3. **Start the development server:**

```bash
npm run dev
```

The app will run at `http://localhost:5173` (if using Vite) or as specified in your setup.

---

## Usage

1. **Add a Todo:** Type in the input field and press **Enter** or click **Add**.  
2. **Edit a Todo:** Click the **✏️ Edit** button next to a todo, modify the text, and click **📁 Save**.  
3. **Complete a Todo:** Check the checkbox to mark a todo as completed. Completed todos have a green background and a strikethrough effect.  
4. **Delete a Todo:** Click the **❌ Delete** button to remove a todo.  
5. **Persistence:** Todos are automatically saved in `localStorage`, so refreshing the page will not lose your data.

---

## File Structure

```
src/
├─ components/
│  ├─ TodoItem.jsx
│  └─ TodoList.jsx
├─ context/
│  └─ TodoContext.jsx
├─ App.jsx
└─ index.jsx
```

- **TodoItem.jsx** – Component for individual todo items (edit, delete, complete).  
- **TodoList.jsx** – Component to render a list of todos.  
- **TodoContext.jsx** – Context API to manage todos globally.  

---

## Technologies Used

- **React** – Frontend library  
- **Tailwind CSS** – Styling  
- **Vite** – Development server & build tool  
- **localStorage** – Browser storage to persist data  

---

## Notes

- The app stores todos in **localStorage**, which is **browser-specific**. Todos will not sync across devices or browsers.  
- Avoid server-side rendering for `localStorage` access. All reads/writes are done inside React hooks like `useEffect`.  

---

## License

This project is open-source and available under the [MIT License](LICENSE).

