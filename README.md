# todo-app
A lightweight, browser-based task manager built with vanilla HTML, CSS and JavaScript. It requires no installation, no build step and no external dependencies. Tasks are saved automatically in the browser and persist between sessions.

Live demo: https://sdepp.github.io/todo-app

Table of Contents
Overview
Features
Getting Started
Technology Stack
Project Structure
How It Works
Roadmap
Contributing
License
Overview

This project demonstrates a minimal but complete front-end application: user input handling, dynamic DOM rendering, state management and client-side persistence. The entire application is contained in a single file, which makes it easy to read, run and extend.

Features
Add new tasks
Mark tasks as completed (completed tasks are displayed with a strikethrough)
Delete tasks
Automatic persistence using the browser's localStorage
Responsive layout that works on desktop and mobile browsers
Zero dependencies
Getting Started
Prerequisites

Any modern web browser (Chrome, Firefox, Safari or Edge).

Installation
Clone the repository:
bash
   git clone https://github.com/sdepp/todo-app.git
Navigate to the project directory:
bash
   cd todo-app
Open index.html in your browser.
Technology Stack
Technology	Purpose
HTML5	Application structure
CSS3	Styling and layout
JavaScript (ES6)	Application logic and data persistence
Project Structure
todo-app/
├── index.html    # Application (markup, styles and logic)
└── README.md     # Project documentation
How It Works
Tasks are stored as an array of objects with the shape { text, done }.
Each action (add, toggle, delete) updates the array, saves it to localStorage and re-renders the list.
When the page loads, previously saved tasks are read from localStorage and displayed.
Roadmap
 Clear all tasks
 Edit existing tasks
 Filter tasks by status (all, active, completed)
 Dark mode
 Due dates and priorities
Contributing

Contributions are welcome. To propose a change:

Fork the repository.
Create a feature branch: git checkout -b feature/your-feature
Commit your changes: git commit -m "Add your feature"
Push the branch: git push origin feature/your-feature
Open a pull request.
License

Distributed under the MIT License. See the LICENSE file for details.

Author

sdepp - GitHub
