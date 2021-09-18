# 2-Deux

## A To-do List App

Add custom tasks with descriptions, due dates, and priority levels. Filter through your tasks via project subfolders, as well as the All Tasks, Today, and This Week subfolders.

Subfolders and their tasks are stored locally so user data is not lost when closing or refreshing the browser.

![demo](dist/to-do-demo.gif)

## Features

### Main Panel

The main panel shows all tasks of the currently selected subfolder.
To delete the current subfolder and subsequently all tasks in it, click the delete button (trash can icon) in the header of the page.

To add your tasks to the current subfolder you are working in, click the plus button in the navbar of the page. Doing so will trigger a pop-up window for you to enter task properties.

Each Task has a checkbox for completion, an edit button, a flag icon illustarting priority level, and a delete button. Each task has a name, description, due date, and priority level. When the task is clicked, a dropdown appears with these properties displayed.

Clicking the edit button of a task causes a pop-up window to appear in which users can edit their task properties. As a task is edited, new property values will take effect for the current task in all subfolders in which it exists.

### Side Panel

The side panel contains three static subfolders: the All Tasks, Today, and This Week subfolders. To add custom subfolders (projects), click the add project button located at the bottom of the side panel.

## Installation

To Work on this project:

Clone project

```bash
git clone https://github.com/Tynasello/to-do-app
```

Change into project directory:

```bash
cd to-do-app
```

Install required dependencies

```bash
npm install
```

To edit JavaScript files work in src/ folder

To update and create distribution files run

```bash
npm run build
```

## Built With

- Vanilla JavaScript
- Webpack
- HTML5
- CSS3

## Acknowledgments

Inspiration for this project was found while following the tutorials on https://www.theodinproject.com/dashboard and advancing to the https://www.theodinproject.com/paths/full-stack-javascript/courses/javascript/lessons/todo-list section
