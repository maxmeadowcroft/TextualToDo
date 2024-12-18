# Donezo

## Overview

Donezo is a visually appealing, terminal based To-Do application built with the Textual framework. It provides a simple interface to manage your tasks with features like saving to CSV, a light/dark mode (you have to manually change), and a polished user experience.

## Features

- **Task management:** Add, delete, and mark tasks as complete.
- **Persistent Storage:** Automatically saves tasks to a CSV file for future sessions.
- **Customizable Themes:**
  - Light and dark more themes with `.tcss` stylesheets.
- **Keyboard and Mouse Support**

## Installation

### Step 1: Clone the Repository

```shell
git clone https://github.com/maxmeadowcroft/Donezo.git
cd Donezo
```

### Step 2: Install Dependencies

Ensure Python 3.8+ is installed then run:

```shell
pip install -r requirements.txt
```

### Step 3: Run the app

```shell
python app/main.py
```

## Usage

- **Add a Task**: Type in the input box and press "Add Item."
- **Delete a Task**: Click the "Delete" button next to a task.
- **Mark as Complete**: Check the box next to a task to mark it as done.
- **Save and Quit**: Your tasks are automatically saved on quit.

## Project Structure

```
Donezo/
├── app/
│   ├── main.py              # Main script
│   ├── styles/              # Stylesheets
│       ├── dark.tcss
│       ├── light.tcss
├── data/
│   ├── todo_items.csv       # Task storage
├── dist/
│   ├── textualtasks-light   # Light mode executable
│   ├── textualtasks-dark    # Dark mode executable
├── .gitignore
├── README.md
├── LICENSE
└── requirements.txt
```

## Customizing Themes

- **Modify Styles**: Edit `light.tcss` or `dark.tcss` in the `app/styles/` folder to change the look and feel of the app.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a feature branch.
3. Submit a pull request.

## License

This project is licensed under the MIT License.

## Contact

Have questions or suggestions? Reach out:

- **GitHub Issues**: Submit a ticket in the [issues section](https://github.com/maxmeadowcroft/Donezo/issues).
- **Email**: maxmeadowcroft61@gmail.com