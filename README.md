# Python Boilerplate

This repo aims to be used as a foundation to new Python projects, covering the basic files and configurations.

## Tools

- Poetry: Python dependency managment
- Visual Studio Code: Text Editor

## Python packages

- mypy
- flake8
- black
- bandit

## Visual Studio code extensions

- Pylance

## 1. Poetry setup

Open terminal and type `poetry init` and go through the options to configure Poetry.

> In this step you can install the required Python packages listed above.

After the prompts, poetry should show the path to the virtual environment. Copy the path and keep to use in the next step.

## 2. Install your Python packages

By typing `poetry add package_name` you can add the packages you need, or you can type `poetry add -D package_name` to add dev dependecies.

## 3. Visual Studio Code configuration

Rename the folder `.vscode.example` to `.vscode`, and change `path_to_virtualenv` with the path provided by Poetry in the previous step.
