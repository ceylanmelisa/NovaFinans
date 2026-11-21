# NovaFinans

NovaFinans is a personal finance dashboard project that I developed using HTML, CSS, and JavaScript. In this project, I practiced working with forms, responsive design, DOM manipulation, and browser-based data storage.

## Features

- Login and registration pages
- Password confirmation validation
- Sample dashboard displaying income, expenses, and account transactions
- Four different color themes
- Drag-and-drop functionality to rearrange, remove, and restore dashboard cards
- Ability to change the number of dashboard columns
- Saving the username, theme, and dashboard layout using `localStorage`

## Files

- `index.html`: Login page
- `register.html`: Registration page and form validation
- `dashboard.html`: Finance dashboard and dashboard settings

## How to Run

No installation is required. Simply open the `index.html` file in a web browser.

## How Does It Work?

When the registration form is submitted, the application checks whether the two passwords match. The user's name is saved in `localStorage` and retrieved when the dashboard is opened. The selected theme, number of columns, card order, and hidden cards are also stored in the browser using `localStorage`.

This project is a frontend interface demonstration. It is not connected to a real server or banking service, and the financial information displayed on the dashboard is sample data.
