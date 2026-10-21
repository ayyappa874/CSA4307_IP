# City Library - Library Management System

A responsive library website built with plain HTML, CSS and JavaScript. Data is stored in the browser (localStorage), so there is nothing to install.

**Live demo:** https://YOUR-USERNAME.github.io/city-library/

## Features

### Librarian (admin)
- Login
- Add, update and delete books
- Issue a book to a student and record its return
- Automatic fine calculation (Rs. 5 per late day, 14-day loan)
- Add, view and delete study material by year and semester

### Student (user)
- Register and login
- Search books by title, author or category, with live availability
- My borrowing history with issue date, due date, status and fine
- Search and download study material by year and semester
- Edit profile

## Demo logins

| Role | Username | Password |
|------|----------|----------|
| Librarian | admin | admin123 |
| Student | student | student123 |

## How to run

Open `index.html` in any browser.

## Technologies

- HTML5
- CSS3 (Flexbox, responsive layout)
- JavaScript (DOM, localStorage, regular functions)

## Project structure

```
city-library/
  index.html
  README.md
```

## Note

This is a front-end learning project (Internet Programming Lab, Experiment 1). Passwords are kept in plain text in localStorage, so a real system would use a server, a database and hashed passwords.
