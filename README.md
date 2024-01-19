<h1>Overview</h1>
    <p>This JavaScript code implements a simple Task Manager, allowing users to add, check, and delete tasks. It utilizes local storage for data persistence.</p>
    <h2>How to Use</h2>
    <ul>
        <li>Open the HTML file in a web browser.</li>
        <li>Enter task details in the input box.</li>
        <li>Click "Add Task" to add the task to the list.</li>
        <li>Click on a task to mark it as completed.</li>
        <li>Click on the 'x' icon to delete a task.</li>
        <li>Refresh the page to see saved tasks.</li>
    </ul>
    <h2>Functions</h2>
    <ul>
        <li><code>addTask()</code>: Adds a task to the list.</li>
        <li><code>save()</code>: Saves the current task list to local storage.</li>
        <li><code>showlist()</code>: Displays tasks from local storage on page load.</li>
    </ul>
    <h2>Event Listeners</h2>
    <ul>
        <li>Listens for clicks on tasks (LI elements) to mark them as completed.</li>
        <li>Listens for clicks on 'x' icons (SPAN elements) to delete tasks.</li>
    </ul>
    <h2>Note</h2>
    <p>Ensure that the HTML file includes an input box with the ID "inputbox" and a container for the task list with the ID "list-container". Feel free to customize the code to fit your specific needs.</p>
