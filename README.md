# Build a Static Site Generator with Python

## Status

**Draft**

## Overview


## Installation

### Windows
Open a command prompt or powershell and run the following commands, replacing 'project-root' with the path to the root folder of the project.
```
> cd 'project-root'
> python -m venv venv
> venv\Scripts\activate.bat
> pip install -r requirements.txt
```

## Verify Setup

In order to verify that everything is setup correctly, run the following command from the project root.
```
pytest
```
You should see that all the tests are failing. This is good! We’ll be fixing these tests once we jump into the build step. Every time you want to check your work locally you can type that command, and it will report the status of every task in the project.

## Previewing Your Work
You can preview your work by running the command `python ssg.py` after the first module.
