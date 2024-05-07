# todo-app-react
1. **Component Structure**:
   - The application consists of two components: `App` and `TodoList`.
   - `App` manages task input, state, and UI rendering.
   - `TodoList` renders the list of tasks and handles their deletion.

2. **State Management**:
   - React's `useState` hook is utilized in both components.
   - In `App`, `task` state stores the current task being inputted, and `todos` state maintains the list of tasks.

3. **Event Handling**:
   - `changeHandler` updates the `task` state as users type in the input field.
   - `submitHandler` adds tasks to the todo list upon form submission, logging them to the console and clearing the input field.
   - `deleteHandler` in `App` removes tasks from the list based on their index.

4. **User Interface**:
   - The UI features a centered card layout titled "Todo Application".
   - Below the title, a form allows users to input tasks.
   - Each task in the list is displayed with a delete button for removal.

5. **Functionality**:
   - Users can input tasks and add them to the list.
   - Tasks are dynamically displayed in the UI as they are added.
   - The application allows users to delete tasks from the list.

6. **Purpose**:
   - Provides a simple and intuitive means of managing todo lists.
   - Suitable for learning React fundamentals or organizing tasks efficiently.
