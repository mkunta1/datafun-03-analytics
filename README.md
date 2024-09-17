# Specification for Project 3 Python Module

## Overview

Project 3 emphasizes skills in using Git for version control, creating and managing Python virtual environments, and handling different types of data.
The project involves fetching data from the web, processing it using appropriate Python collections, and writing the processed data to files.

## Deliverable Names

- GitHub Repository:  **datafun-03-analytics**
- Documentation:      README.md
- Script:             **yourname_analytics.py**

## Start a New Project

Follow this common workflow to start a new project.

1. In your browser, create a GitHub project repository with a default README.md. Name the repo as specified above.
2. Clone your new repository down to your machine into your Documents folder.
3. Open your new project repository folder in the Documents folder of your machine in VS Code (if you haven't already).
4. In VS Code, add a useful .gitignore file with a line for .vsode/ and .venv/ and whatever else doesn't need to be tracked in the repository.
5. In VS Code, edit your README.md to record your commands, process, and notes so far.
6. In VS Code, open a terminal - PowerShell if Windows, zsh or bash if Mac/Linux.
7. Use the terminal to git add your files and folders to source control, and git commit your changes with a useful message (e.g. "initial commit"), and git push the changes up to GitHub.
8. Verify your GitHub repository.

## Objective

Create a Python module that demonstrates skills in fetching data from the web, processing it using Python collections, and writing the processed data to different file formats.

## Requirements

### 1. Create and Manage Project Virtual Environment

This project uses the requests package, which is not included in the Python Standard Library - we must install it. 
To keep our project separate from all other Python projects,
we will create and manage a local project virtual environment.
We'll install our packages into the local project virtual environment.
For the recommended process with detailed steps and commands, see [PROJECT_VIRTUAL_ENV.md](PROJECT_VIRTUAL_ENV.md).