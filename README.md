# CODETECH TASK-2

Name: R.Ram harish
Company: CODETECH IT SOLUTIONS
ID:CT08DS564
Domain : SOFTWARE DEVELOPEMENT
Duration : December 12th, 2024 to january 12th, 2025

#OVERVIEW OF THE PROJECT

OBJECTIVE:The project is a **Task Management Tool** designed to help users manage and track their tasks efficiently. It is built using HTML, CSS, and JavaScript, with a clean, user-friendly interface. Here’s a breakdown of the project:

### 1. **Features**
   - **Task Creation**: Users can enter a task name into an input field and add it to the list by clicking the "Add Task" button.
   - **Task Completion**: Each task has a "Complete" button that allows users to mark a task as completed. When completed, the task's name is struck through.
   - **Task Deletion**: Users can delete tasks using the "Delete" button next to each task.
   - **Interactive Interface**: The tasks list is dynamically updated as tasks are added, completed, or deleted.
   - **Hover Effects**: Tasks have a hover effect for a smooth user experience, with the task "growing" slightly when hovered over.
   
### 2. **Design and Layout**
   - **Header**: Displays the title "Task Management Tool" in a dark background with white text. It uses a flexbox layout for responsive positioning.
   - **Main Area**: Includes an input field for entering tasks and a list where tasks are displayed. Each task is styled with a white background, rounded corners, and a subtle shadow to make them visually distinct.
   - **Buttons**: Interactive buttons are used for adding, completing, and deleting tasks. Buttons change color when hovered over to provide feedback to the user.
   - **Task List**: Tasks are displayed as individual cards with a title (task name) and action buttons for completing or deleting the task.

### 3. **Functionality (JavaScript)**
   - **Adding Tasks**: The function `addTask()` adds a new task to the `tasks` array, and then the `renderTasks()` function is called to update the display.
   - **Toggling Completion**: The `toggleTaskCompletion()` function marks a task as completed or uncompleted by updating the `completed` property of the task object.
   - **Deleting Tasks**: The `deleteTask()` function removes a task from the `tasks` array.
   - **Dynamic Rendering**: The tasks are rendered dynamically in the browser as the user interacts with the interface. This is achieved by manipulating the DOM using JavaScript.

### 4. **Styling (CSS)**
   - The styling is simple, using flexbox for layout and providing visual feedback through hover effects and transitions. 
   - The buttons have distinct colors for different actions, and the layout is responsive and clean, with a modern, minimal design.

### 5. **User Experience**
   - The interface is intuitive, with tasks clearly presented and simple actions (complete, delete) easily accessible.
   - The use of animations and transitions (e.g., task hover effect) creates a smooth experience for the user.

### 6. **Code Structure**
   - **HTML**: Defines the basic structure, including the header, task input form, and task list container.
   - **CSS**: Styles the layout, making it visually appealing and responsive.
   - **JavaScript**: Manages task data, updates the user interface dynamically, and handles user interactions.

This project serves as a basic, functional task management tool with room for further expansion, such as adding task priorities, deadlines, or persistence (e.g., saving tasks to local storage or a database).
