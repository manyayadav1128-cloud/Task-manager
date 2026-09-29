# 📝 Task Manager

A simple and user-friendly **Task Manager web application** developed using **HTML, CSS, and JavaScript**. The application helps users create, manage, update, complete, and delete their daily tasks.

The project demonstrates practical knowledge of **frontend web development, CRUD operations, JavaScript DOM manipulation, Local Storage, input validation, and software testing**.

---

## 📌 Project Overview

The Task Manager provides a simple digital solution for managing daily tasks from a single interface.

Users can create new tasks, edit existing tasks, mark tasks as completed, and delete tasks when they are no longer required.

The application uses **Browser Local Storage** to maintain task data even after refreshing the page.

### Main Operations

* **Create** – Add a new task
* **Read** – View existing tasks
* **Update** – Edit an existing task
* **Delete** – Remove a task

---

## ✨ Features

### ➕ Add Task

Users can enter a task and add it to the task list.

### ✏️ Task Completion

Users can mark tasks as completed or pending.

### ✅ Complete Task

Users can mark a task as completed.

### 🗑️ Delete Task

Users can remove tasks from the task list.

### 💾 Local Storage

Task data is stored in the browser's Local Storage so that tasks remain available after refreshing the page.

### 🔄 Dynamic UI

The task list is dynamically updated using JavaScript without requiring a page reload for every operation.

### ⚠️ Input Validation

The application handles invalid or empty task input to prevent unnecessary task entries.

---

# 🛠️ Technologies Used

| Technology        | Purpose                                |
| ----------------- | -------------------------------------- |
| **HTML5**         | Structure of the web application       |
| **CSS3**          | Styling and user interface             |
| **JavaScript**    | Application logic and DOM manipulation |
| **Local Storage** | Persistent browser-based task storage  |
| **Git**           | Version control                        |
| **GitHub**        | Source code management                 |

---

# 🏗️ Project Structure

```text
Task-Manager/
│
├── index.html
├── style.css
├── script.js
│
├── testing/
│   ├── test-cases.md
│   └── bug-reports.md
│
└── README.md
```

> The file and folder names should match the actual structure of the repository.

---

# ⚙️ How the Application Works

The application follows a simple task management workflow:

```text
User
  ↓
Enter Task
  ↓
Input Validation
  ↓
Add Task
  ↓
Task Displayed
  ↓
 ┌───────────────┐
 │               │
Edit          Complete
 │               │
 ↓               ↓
Update        Change Status
 │               │
 └───────┬───────┘
         ↓
    Local Storage
         ↓
       Delete
```

### Workflow

1. The user enters a task.
2. The application validates the input.
3. The task is added to the task list.
4. Task information is stored in Local Storage.
5. The user can edit, complete, or delete the task.
6. Changes are reflected in the interface and stored data.

---

# 💾 Data Storage

The application uses **Browser Local Storage** to store task information.

This allows tasks to remain available after refreshing the browser.

Example:

```javascript
localStorage.setItem("tasks", JSON.stringify(tasks));
```

Stored data can be retrieved using:

```javascript
localStorage.getItem("tasks");
```

No separate backend or database is required for this project.

---

# 🧪 Testing

The application was tested from a **functional and user-interaction perspective** to verify that its main features behave according to their expected requirements.

## Testing Types

The following testing approaches are considered for the application:

* Functional Testing
* Positive Testing
* Negative Testing
* Input Validation Testing
* UI Testing
* Retesting
* Regression Testing
* Basic Usability Testing

---

## 🔍 Test Scenarios

| Test Case | Scenario                    | Expected Result                                    |
| --------- | --------------------------- | -------------------------------------------------- |
| TC-01     | Add a valid task            | Task should be added successfully                  |
| TC-02     | Submit an empty task        | Application should handle invalid input            |
| TC-03     | Add multiple tasks          | All valid tasks should be displayed correctly      |
| TC-04     | Edit an existing task       | Selected task should be updated                    |
| TC-05     | Delete a task               | Selected task should be removed                    |
| TC-06     | Mark a task as completed    | Task status should change                          |
| TC-07     | Refresh the page            | Stored tasks should remain available               |
| TC-08     | Delete a completed task     | Selected task should be removed                    |
| TC-09     | Enter invalid input         | Application should handle the input appropriately  |
| TC-10     | Perform multiple operations | Application should maintain the correct task state |



---

# 🐞 Bug Identification & Reporting

During testing, unexpected application behavior can be identified and documented as defects.

A bug report can contain:

* Bug ID
* Bug Title
* Steps to Reproduce
* Expected Result
* Actual Result
* Severity
* Priority
* Status

### Example Bug Report

```text
Bug ID: BUG-01

Title:
Empty task submission

Steps to Reproduce:
1. Open the Task Manager.
2. Leave the task input field empty.
3. Click the Add button.

Expected Result:
Application should display an appropriate validation message.

Actual Result:
Record the actual behavior observed during testing.

Severity:
Medium

Priority:
Medium

Status:
Open / Fixed
```



---

# 📂 Testing Documentation

Detailed testing information is maintained in the `testing` folder.

```text
testing/
│
├── test-cases.md
└── bug-reports.md
```

### `test-cases.md`

Contains:

* Test Case ID
* Test Scenario
* Test Steps
* Expected Result
* Actual Result
* Status

### `bug-reports.md`

Contains:

* Bug ID
* Bug Description
* Steps to Reproduce
* Expected Result
* Actual Result
* Severity
* Priority
* Bug Status

---

# 🚀 How to Run the Project

## Prerequisites

You only need:

* A modern web browser
* Git (optional, for cloning the repository)

No backend server or database setup is required.

## Steps

### 1. Clone the repository

```bash
git clone YOUR_REPOSITORY_LINK
```

### 2. Open the project folder

```bash
cd Task-Manager
```

### 3. Run the application

Open the `index.html` file in your web browser.

The application will start directly in the browser.

---

# 🌐 Live Demo

**Live Project:**
Add your deployed project link here.

Example:

```text
https://your-task-manager.vercel.app
```

---

# 📈 Future Enhancements

The project can be further improved by adding:

* User authentication
* Task categories
* Task priority levels
* Due dates and reminders
* Search and filtering
* Dark mode
* Backend integration
* Database support
* Automated testing
* Selenium-based test automation
* API integration with a backend
* Improved accessibility

---

# 🎯 Learning Outcomes

Through this project, I gained practical experience in:

* HTML, CSS, and JavaScript development
* DOM manipulation
* JavaScript event handling
* CRUD operations
* Browser Local Storage
* User input validation
* Dynamic UI development
* Debugging and problem solving
* Creating test scenarios
* Functional testing
* Positive and negative testing
* Identifying and documenting defects
* Retesting application functionality
* Using Git and GitHub for version control

---

# ⭐ Project Highlights

* ✔️ Frontend web application
* ✔️ CRUD-based task management
* ✔️ Local Storage implementation
* ✔️ Dynamic user interface
* ✔️ Input validation
* ✔️ Functional testing
* ✔️ Positive and negative test scenarios
* ✔️ Bug identification and reporting
* ✔️ GitHub version control
* ✔️ Deployed web application

---

