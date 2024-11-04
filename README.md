# Todo List App

Welcome to the **Todo List App**, a robust application designed to help users manage their tasks effectively. This app allows you to track daily chores, work projects, and personal goals through an intuitive and user-friendly interface.


## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Challenges Faced](#challenges-faced)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Features

### 1. Add Tasks
- **Description**: Users can easily add new tasks using a simple input field. This feature allows users to enter a description of the task and an optional due date.
- **Implementation**: The input field captures user input, and upon clicking the "Add Task" button or pressing `Enter`, the task is added to the list. It utilizes JavaScript to manipulate the DOM and update the task list dynamically.

### 2. View Tasks
- **Description**: The app displays a list of all tasks, providing users with a clear overview of their to-do items. Users can filter tasks based on their completion status.
- **Implementation**: Tasks are categorized into three views: All, Active, and Completed. Filtering is implemented using JavaScript to dynamically show or hide tasks based on user selection.

### 3. Delete Tasks
- **Description**: Users can remove tasks from their list. This feature includes a confirmation dialog to prevent accidental deletions.
- **Implementation**: Each task includes a "Delete" button. When clicked, a confirmation dialog appears. If confirmed, the task is removed from the DOM and the local storage.

### 4. Edit Tasks
- **Description**: Users have the ability to modify existing tasks. This feature allows for updates to task descriptions and due dates.
- **Implementation**: Clicking on a task enters edit mode, allowing users to modify the text. Changes are saved in real-time to local storage, ensuring persistence.

### 5. Mark as Completed
- **Description**: Users can easily toggle tasks between active and completed states. Completed tasks are visually distinguished from active ones.
- **Implementation**: A checkbox next to each task allows users to mark it as completed. The task's visual representation changes to indicate its status, utilizing CSS for styling.

### 6. Persistent Storage
- **Description**: The app uses local storage to save tasks, ensuring that data is retained even after the browser is refreshed or closed.
- **Implementation**: JavaScript's local storage API is used to store and retrieve tasks, allowing users to maintain their task list across sessions.

### 7. Responsive Design
- **Description**: The application is fully responsive, providing an optimal experience on various devices, including desktops, tablets, and mobile phones.
- **Implementation**: CSS media queries are utilized to adjust the layout and styling based on the screen size, ensuring usability on different devices.

### 8. User-Friendly Interface
- **Description**: The app is designed with a focus on user experience, featuring a clean layout and intuitive navigation.
- **Implementation**: The interface is built using semantic HTML and styled with CSS to create a visually appealing and easy-to-navigate environment.

## Technologies Used

- **HTML**: For structuring the application, including the layout and elements such as input fields, buttons, and task lists.
- **CSS**: For styling the application, ensuring a visually appealing interface that is consistent across different screen sizes.
- **JavaScript**: For implementing the dynamic functionalities, including task management (adding, editing, deleting, and marking tasks).
- **Local Storage**: To save tasks and ensure data persistence, allowing users to access their tasks even after closing the application.


## Challenges Faced

1. **State Management**: 
   - **Challenge**: Managing the state of tasks (active vs. completed) in a way that is easy for users to understand.
   - **Solution**: Implemented clear visual cues and filters to distinguish between task states.

2. **Data Persistence**:
   - **Challenge**: Ensuring that tasks are retained after refreshing the page.
   - **Solution**: Utilized the local storage API to store tasks in the browser, which allows for data retention across sessions.

3. **User Experience**:
   - **Challenge**: Creating a seamless and intuitive user experience.
   - **Solution**: Conducted user testing to gather feedback and iterated on the design to improve usability.

4. **Responsive Design**:
   - **Challenge**: Ensuring the app looks good on all devices.
   - **Solution**: Employed CSS media queries and flexible layouts to adapt the interface to different screen sizes.

