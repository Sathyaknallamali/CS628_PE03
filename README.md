# Input
Users can type in task descriptions in only one input field.  When a user types something into the field and hits the "Add Task" button, the input is saved and processed.  Each task item should be a short written description of what the user wishes to add to their ToDo list.

# Process
The app leverages React's `useState` hook to keep track of a changing list of tasks.  If the list isn't empty, clicking the "Add Task" button will add the item to it.  The `.map()` function shows each task.  Each task is stored in its own component, and pressing the "Delete" button eliminates the task at the index in the array.  Custom event listeners handle all interactions, making sure that updates happen smoothly without reloading the website.

# Output
Below the input box, users can see a list of jobs that has been changed.  There is a "Delete" button for each task that lets you remove it.
