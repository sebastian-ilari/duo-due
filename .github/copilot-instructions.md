# Project description

This is a simple web application designed to help two users track their expenses and calculate the debt towards each other.

## Project guidelines

* Use Domain Driven Design (DDD) principles to structure the application
* Write clean, maintainable, object-oriented code
* Keep files and folder names descriptive and meaningful
* The backend and frontend should be separated into different projects within the duo-due solution

## Technology stack

* Backend: C# .NET Core
* Frontend: Blazor webassembly
* Database: PostgreSQL

## Frontend guidelines

* Frontend logic, HTML markup and CSS style definitions should be in different files
* The application should be responsive and work well on both desktop and mobile devices
* The whole application runs in a single page without full page reloads
* Use standard UX design patterns
* Use the following color palette throughout the application: #e63946, #f1faee, #a8dadc, #457b9d, #1d3557
* Use a consistent typography throughout the application

## Backend guidelines

* Add unit and integration tests to cover all business logic
* The application maintains a persistent state in the browser, so that users can refresh the page without losing their data
* The current debts are persisted in the database, so they don't have to be calculated based on all the expenses every time the page is loaded
