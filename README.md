
# Week 07: JavaScript Best Practices 

## Author
- **Name:** Calvin Mutungi Wambui
- **GitHub:** [@CalvinMutungi](https://github.com/CalvinMutungi)
- **Date:** November 13, 2026

## Project Description
A refactored and improved version of the Week 05 To-Do List application, focusing on professional JavaScript development practices, modular code architecture, persistent state management, automated testing, and code quality. The project demonstrates the ability to organize JavaScript applications into reusable modules, maintain data using browser storage, and write clean, maintainable, and testable code.

## Technologies Used
- HTML5
- CSS3
- JavaScript (ES6+)
- Node.js
- ESLint
- Prettier
- Vitest
- Git & GitHub

## Features
- **Persistent Data Storage:** Uses `localStorage` to preserve tasks and application state across page refreshes.
- **Modular Architecture:** Separates application logic into reusable modules for state management, storage, UI manipulation, and task operations.
- **Centralized State Management:** Maintains a single source of truth for application data and ensures consistent updates.
- **Pure Functions:** Implements reusable task operations that can be tested independently without DOM or browser dependencies.
- **Automated Unit Testing:** Uses Vitest to test core application logic, including adding, toggling, deleting, filtering, and counting tasks.
- **Code Quality Enforcement:** Uses ESLint to identify errors and enforce JavaScript best practices.
- **Consistent Code Formatting:** Integrates Prettier to maintain readable and consistent code.
- **Data Validation:** Handles invalid or corrupted stored data safely to prevent application crashes.

## How to Run
1. Clone this repository:

   ```bash
   git clone https://github.com/CalvinMutungi/iyf-s12-week-07-CalvinMutungi.git
   ```

2. Navigate into the project directory:

   ```bash
   cd iyf-s12-week-07-CalvinMutungi
   ```

3. Install the project dependencies:

   ```bash
   npm install
   ```

4. Run the development environment using Live Server or another local development server.

5. Open the application in your browser.

6. Run the unit tests:

   ```bash
   npm test
   ```

7. Run ESLint to check code quality:

   ```bash
   npm run lint
   ```

8. Format the project files using Prettier:

   ```bash
   npm run format
   ```

## Lessons Learned
- Gained a deeper understanding of persistent data management using `localStorage`, `sessionStorage`, and JSON serialization.
- Learned to structure larger JavaScript applications using ES6 modules and separate files based on responsibility.
- Improved understanding of centralized state management and the observer pattern.
- Practised writing pure functions that transform data without directly interacting with the DOM or browser storage.
- Learned to apply clean code principles, including meaningful naming conventions, single responsibility, and avoiding magic numbers.
- Developed debugging skills using browser DevTools, console methods, and breakpoints.
- Gained practical experience configuring ESLint and Prettier to enforce code quality and consistent formatting.
- Learned the fundamentals of unit testing using Vitest, including testing edge cases and ensuring functions do not mutate original data.
- Improved understanding of Git workflows, branching, pull requests, and collaborative peer code reviews.

## Challenges Faced
- Refactoring the original To-Do List application into independent modules while maintaining communication between application logic, state management, storage, and UI components.
- Handling invalid or corrupted JSON data in localStorage without causing application crashes.
- Configuring ESLint 9 using the new `eslint.config.js` flat configuration system.
- Setting up Vitest and ensuring that pure JavaScript functions could be tested independently.
- Maintaining consistency between application state, localStorage, and dynamically rendered DOM elements.
- Managing dependencies and ensuring that `node_modules/` was excluded from version control.

### How I Solved Them
- Separated application responsibilities into dedicated JavaScript modules using ES6 imports and exports.
- Implemented `try/catch` error handling when retrieving and parsing stored data.
- Configured ESLint and Prettier using their recommended modern configurations.
- Extracted core task operations into pure functions to make them easier to test.
- Used centralized state updates to keep application data and the interface synchronized.
- Added `node_modules/` to `.gitignore` and committed the necessary dependency files.

## Collaboration
- **Team / Partner:** Solo implementation
- **Shared Repository:** N/A
- **PR I Opened:** N/A
- **PR I Reviewed:** N/A
- **Merge Conflict I Resolved:** N/A

## Screenshots (optional)

## Live Demo (if deployed)
[View Live Demo](https://your-deployed-url.com)
