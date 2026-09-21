# To-Do List Website

## Overview

**To-Do List** is a browser-based task management website created as a practice project to strengthen my understanding of **HTML, JavaScript, browser storage, objects, and JSON-based data handling**.

The application allows users to add, edit, complete, and delete tasks while maintaining task data using the browser's **Local Storage**.

---

## Features

* Add new tasks
* Add tasks using the **Save** button or **Enter** key
* Mark tasks as completed using checkboxes
* Edit existing tasks
* Delete individual tasks
* Delete all tasks
* Automatically restore saved tasks after refreshing the page
* Store task data using browser Local Storage
* Handle task data using JavaScript
* Use objects/JSON concepts for working with structured data

---

## Technologies Used

* **HTML5** — Page structure and input elements
* **JavaScript** — Application logic and DOM manipulation
* **Local Storage** — Persistent browser-side data storage
* **JavaScript Objects** — Working with structured application data
* **JSON** — Data representation and handling concepts

---

## How It Works

The application follows a simple client-side data flow:

```text
User Enters Task
       ↓
JavaScript Processes Input
       ↓
Task Added to the Page
       ↓
Task Data Stored in Local Storage
       ↓
Data Retrieved When Page Loads
       ↓
Tasks Displayed Again
```

---

## Task Operations

### Add Task

Users can enter a task and click **Save** or press **Enter**.

Empty inputs are ignored.

### Complete Task

Each task has a checkbox. When checked, the task is visually marked as completed using a strikethrough effect.

### Edit Task

The edit button allows the user to modify an existing task. The updated task is also reflected in the stored data.

### Delete Task

Individual tasks can be removed from both the page and Local Storage.

### Delete All

The **DeleteAll** button removes all saved tasks after confirmation.

---

## Local Storage

The project uses the browser's **Local Storage API** to keep tasks available even after the page is refreshed or reopened.

The application uses a dedicated storage key:

```javascript
const key = "todo";
```

Data is retrieved using:

```javascript
localStorage.getItem(key);
```

and stored using:

```javascript
localStorage.setItem(key, data);
```

The project also demonstrates converting stored task data into an array for operations such as editing, deleting, and displaying tasks.

---

## Data Handling

The project provided practice with:

* JavaScript variables and functions
* Arrays
* Objects
* JSON/data representation concepts
* String manipulation
* Local Storage
* DOM creation and manipulation
* Event listeners
* User input handling
* Array methods such as `split()` and `filter()`

---

## Core Application Flow

```text
Page Loads
    ↓
Read Tasks from Local Storage
    ↓
Convert Stored Data
    ↓
Create Task Elements
    ↓
Display Tasks
    ↓
User Performs an Action
    ↓
Update Page + Stored Data
```

---

## Project Structure

```text
To-Do-List-Website/
│
├── index.html
└── README.md
```

The application logic is currently contained within the HTML file using JavaScript.

---

## How to Run

1. Clone or download the repository.
2. Open the project folder.
3. Open `index.html` in a modern web browser.
4. Start adding tasks.

No backend, database, or external installation is required.

---

## Skills Demonstrated

This project demonstrates practical understanding of:

* HTML
* JavaScript fundamentals
* DOM manipulation
* Event-driven programming
* Local Storage
* Arrays and data manipulation
* Objects and JSON concepts
* CRUD-style operations on client-side data
* User input validation
* Browser-based application state

---

## Project Status

**Completed**

This project was created as a practice application to strengthen my JavaScript fundamentals and understand how browser-side storage can be used to build a persistent interactive web application.

---

## Author

**Jyotsana**

BCA | Data Analytics
Python | SQL | Excel | Power BI | JavaScript | Web Development
