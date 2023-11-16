# Taskify

Taskify is a simple task management application built using TypeScript and React. It allows users to add, edit, mark as done, and delete tasks. The application utilizes the `react-beautiful-dnd` library for smooth drag-and-drop functionality to organize tasks.

## Features

- **Add Task:** Enter a task in the input field and click "Go" to add it to the active tasks list.
- **Edit Task:** Click on the edit icon to modify the task description.
- **Mark as Done:** Click on the checkmark icon to mark a task as done.
- **Delete Task:** Click on the trash bin icon to delete a task.
- **Drag-and-Drop:** Use drag-and-drop to reorder tasks within the active tasks list and move completed tasks to the "Completed Tasks" section.

## Technologies Used

- React
- TypeScript
- `react-beautiful-dnd`

## Code Structure

- **App.tsx:** The main component that integrates the input field, task lists, and drag-and-drop functionality.
- **TodoList.tsx:** Component responsible for rendering the active and completed task lists, utilizing `react-beautiful-dnd` for drag-and-drop.
- **SingleTodo.tsx:** Component for rendering individual tasks, including editing, marking as done, and deleting functionality.
- **InputField.tsx:** Component for the input field used to add new tasks.

## Styling

The application features a clean and responsive design. Media queries are used to optimize the layout for various screen sizes.

# Acknowledgment

This project was completed during a TypeScript and React crash course, and I'm grateful for the valuable learning experience it provided.
