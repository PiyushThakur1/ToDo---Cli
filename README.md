# ToDo CLI

A simple and customizable command-line Todo application built with **Node.js**, using `chalk` for styling and `commander` for commands.

---

##  Features

- Add tasks
- List all tasks (color-coded)
- Edit tasks
- Delete individual tasks
- Delete all tasks
- Mark tasks as done
- Stylish output using Chalk
- Data is saved in a local JSON file (`todo.json`)

---


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/PiyushThakur1/ToDo---Cli.git
   cd ToDo---Cli

2. Install Dependencies

```bash
  npm install
```
3. Run the Cli

```bash
 node index.js
```
4. Add a task

```bash
  node index.js add "Buy groceries"
```
5. List all tasks

```bash
 node index.js list
```

6. Edit a task

```bash
  node index.js edit <task_number> "New task text"
```
7. Delete a task

```bash
 node index.js delete <task_number>
```
8. Add a task

```bash
  node index.js add "Buy groceries"
```
9. Delete all tasks

```bash
 node index.js deleteAll

```


## Tech Stack

Node.js

Commander

Chalk