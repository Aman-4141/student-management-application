# Student Management Application

A frontend-only student roster manager. Student records are stored in the browser's local storage; no backend or build step is required.

## Run

Open `index.html` in a browser, or start a local static server from the project directory:

```powershell
py -m http.server 8081
```

Then visit <http://localhost:8081>. The included VS Code launch configuration uses this address.

## Features

- Add students with a unique student ID, name, course, and mark from 0 to 100.
- Remove students from the roster.
- Search students and filter the roster by course.
- View the student count, class average, and number of courses.
- See a letter grade calculated from each mark.
- Keep records across page reloads with local storage.

Student data stays in the current browser and is not synced between devices. To clear all records, remove the `northstar-students` item from the browser's local storage.