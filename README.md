# kanban-board
Project Structure:
src/
├── components/
│   ├── TaskBoard.jsx
│   ├── TaskColumn.jsx
│   ├── TaskCard.jsx
│   ├── TaskForm.jsx
│   └── EditTaskModal.jsx
├── context/
│   └── TaskContext.jsx
├── App.jsx
└── main.jsx

Create, edit, delete, and move tasks across To Do, In Progress, and Done columns.
Built with React Hooks (useState, useEffect, useContext) and styled using TailwindCSS.
Responsive layout: columns stack on mobile and align in three columns on desktop.
The TaskForm is to create tasks—enter title, description, and status.
Each TaskCard has “Edit” and “Delete” buttons.
Edit opens a modal to update title, description, or status.
Delete removes the task immediately.
All task updates are saved in localStorage, ensuring your board stays intact on reload.

