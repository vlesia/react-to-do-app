# React To-Do App

## Overview

The React To-Do App is a simple yet powerful task management application built using React. It allows users to create, edit, delete, and mark tasks as completed.

## Demo

Check out the [DEMO]() to see the project in action!

## Technologies Used

- **React:** The core framework used for building the user interface and managing state.
- **TypeScript:** TypeScript is used to add static typing to JavaScript, providing better code quality and developer experience.
- **SCSS:** SCSS is used for styling to enhance maintainability and modularity.
- **GitHub Actions:** GitHub Actions are used for continuous integration and deployment, automating the build and deployment process.

## Features

### Task Management

- **Create Tasks:** Easily create new tasks by typing in the task description and pressing enter or clicking the add button.
- **Edit Tasks:** Update task details by clicking on the task name or description. This opens an editable field where you can make changes.
- **Delete Tasks:** Remove tasks individually by clicking on the delete icon next to each task. There's also an option to delete all completed tasks at once.
- **Mark as Completed:** Mark tasks as completed by checking the checkbox next to each task. Completed tasks are visually distinguished from active ones.

### Data Management

- **Local Storage:** Task data is stored locally using browser storage, ensuring that your tasks are saved even if you close the browser or refresh the page.

## Getting Started

### Prerequisites

Ensure you have the following installed:

Node.js (v14.21.3)

### Installation
1. Clone the repository:
```bash
git clone https://github.com/vlesia/react-to-do-app.git
```
2. Navigate to the project directory:
```bash
cd nothing-landing
```
3. Install dependencies:
```bash
npm install
```
4. To run the project in your browser:
```bash
npm start
```

## Folder Structure

The project follows a standard folder structure for better organization:

```graphql
react-to-do-app/
├── public/               # Public assets
├── src/                  # Source files
│   ├── components/       # React components
│   └── utils/            # Utility functions
|   └── ...
|
│── .gitignore          # Git ignore file
│── README.md           # Project documentation
└── package.json        # Project metadata and dependencies
```

## Contributing

We welcome contributions to the React To-Do App! If you have suggestions for new features, improvements, or bug fixes, please, fork the repository and create a pull request with your changes.


## License

This project is licensed under the MIT License.