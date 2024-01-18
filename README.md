1) Calculator
   ============

   ### Project Overview:

The provided HTML, CSS, and JavaScript code represents a simple calculator web application. The calculator allows users to perform basic arithmetic operations and includes features such as clearing the input, deleting the last character, and calculating the result.

### HTML Structure:

- **DOCTYPE and Language:** Declares the document type and specifies the language as English.
- **Head Section:** Contains meta tags for character set and viewport, sets the title, and links the CSS file.
- **Body Section:** Divided into a main container with two sections - "output" and "buttons." The "output" section includes an input field for displaying the calculator's output, and the "buttons" section contains various buttons for numbers, operators, and control functions.

### CSS Styling:

- **Global Styles:** Sets global styles for the body, including font, display properties, background color, and alignment.
- **Main Container Styles:** Defines styles for the calculator container, including width, background color, padding, and border radius.
- **Button Styles:** Styles the calculator buttons, setting the font size, border-radius, and cursor, with special styling for operator buttons ("op").
- **Output Styles:** Styles the output/input field, setting the width, padding, font size, text alignment, and pointer-events to prevent user input.

### JavaScript Functionality:

- **Button Selection:** Uses JavaScript to select all buttons and the input field.
- **Event Listeners:** Adds event listeners to each button, listening for click events.
- **Switch Statement:** Implements a switch statement to handle different button clicks.
  - **"=" Button:** Evaluates the expression and updates the input field with the result.
  - **"AC Button:** Clears the input field and resets the string.
  - **"DE" Button:** Removes the last character from the string.
  - **Number and Operator Buttons:** Appends the corresponding value to the string and updates the input field.

### Responsive Design:

- The calculator has a responsive design with a fixed width for the main container, ensuring a consistent appearance across different devices.

### Note:

- The calculator uses the `eval` function to evaluate mathematical expressions. While it simplifies the code, it may have security implications if used with untrusted input. A more robust approach could involve parsing and evaluating expressions manually.

- The design is kept minimalistic, and the calculator is functional for basic arithmetic operations. Additional features, error handling, or a more sophisticated design could be implemented based on project requirements.

2) To-do list
   ============
   ### Project Overview:

The provided HTML, CSS, and JavaScript code represents a simple To-Do List web application. The application allows users to add, mark as complete, and delete tasks. The design is visually appealing, and it incorporates local storage to persist tasks even after the page is refreshed.

### HTML Structure:

- **DOCTYPE and Language:** Declares the document type and specifies the language as English.
- **Head Section:** Contains meta tags for the viewport, sets the title, and links the CSS file.
- **Body Section:** Contains a container with a To-Do List app. The app includes a header, an input field for adding tasks, a button to add tasks, and a list container to display tasks. The list items include a checkbox, the task text, and a delete button.

### CSS Styling:

- **Global Styles:** Sets global styles for the body, including font, display properties, background color, and alignment.
- **Container Styles:** Styles the main container, setting the width, background color, and padding.
- **To-Do App Styles:** Styles the To-Do app, including width, maximum width, background color, margin, padding, and border radius.
- **Header Styles:** Styles the header, including the title, color, and alignment.
- **Input and Button Styles:** Styles the input field, button, and row, defining their appearance, colors, and alignment.
- **List Item Styles:** Styles the list items, checkboxes, and delete buttons, setting the font size, padding, user-select, cursor, and position. Different styles are applied to checked items and delete buttons on hover.

### JavaScript Functionality:

- **Task Addition:** Defines a function (`addTask`) to add tasks to the list container. It checks if the input is empty and displays an alert if so.
- **Event Listeners:** Adds event listeners to the list container for handling clicks on list items and delete buttons.
- **Toggle Checked State:** Toggles the "checked" class on list items when clicked, marking them as complete or incomplete.
- **Delete Task:** Removes a task when the delete button is clicked.
- **Local Storage:** Implements functions (`saveData` and `showTask`) to save and retrieve tasks from local storage, ensuring persistence across page reloads.

### Responsive Design:

- The To-Do List app has a responsive design with a maximum width for the app container, ensuring it displays well on various devices.

### Note:

- The application uses `localStorage` to store and retrieve task data, allowing users to access their tasks even after refreshing the page.
- The design is clean and user-friendly, providing essential functionality for managing a To-Do List. Additional features or improvements, such as due dates, categories, or task priorities, could be implemented based on project requirements.

3)Registration Form
# Registration Form Project Overview

## Project Description

The Registration Form project is a web application developed using HTML, CSS, and JavaScript. It provides users with a simple interface for entering personal information such as first name, last name, email, mobile number, and age. The entered data is dynamically added to a table for display.

## Technologies Used

- **HTML:** Defines the structure and elements of the registration form.
- **CSS:** Styles the visual presentation, ensuring a clean and user-friendly design.
- **JavaScript:** Implements interactivity, allowing users to add their information dynamically to a table.

## Project Components

### 1. HTML Structure

- **DOCTYPE and Language:** Specifies the document type and language.
- **Head Section:** Contains meta tags, title, and links to external stylesheets and scripts.
- **Body Section:** Includes a centered registration form with input fields for first name, last name, email, mobile number, and age. It also has a button for adding the entered data to a table.

### 2. CSS Styling

- **Table Styles:** Defines styling for the tables, including margin, text alignment, background color, and text color.
- **Button Styles:** Styles the "Add" button, setting the width to 100%.
- **Responsive Design:** Ensures a responsive layout for a consistent appearance across different devices.

### 3. JavaScript Functionality

- **Arrays:** Uses arrays to store entered data for first name, last name, email, mobile number, and age.
- **Counters:** Utilizes counters to keep track of the number of rows in the table.
- **AddRow Function:** Dynamically adds a new row to the table with the entered data when the "Add" button is clicked.

## Notes

- **Data Storage:** The project currently uses separate arrays for each piece of information. Consider using objects or a more structured data approach.
- **Validation:** Implement data validation to ensure that required fields are not empty and meet specific criteria.
- **Security:** For a production environment, handle user data on the server side with proper validation and sanitation.
- **Improvements:** Depending on project requirements, consider adding additional features, error handling, or a more sophisticated design.
