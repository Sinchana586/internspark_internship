# internspark_internship
# File Cleanup and Renaming Automation

## Overview
This project is a Python-based automation script that performs file management tasks automatically. It helps organize files by removing empty files and renaming existing files into a standardized format. The script also maintains a log of all operations performed, making it easy to track changes.

## Features
- Accepts a folder path from the user.
- Detects and deletes empty files.
- Renames files using a consistent naming convention.
- Generates a log file containing details of all operations.
- Uses exception handling to manage errors gracefully.
- Built using Python's OS module for file and directory operations.

## Technologies Used
- Python 3
- OS Module
- Datetime Module

## Working
1. The user enters the path of the target folder.
2. The script scans all files in the folder.
3. Empty files are identified and deleted.
4. Remaining files are renamed sequentially.
5. Every operation is recorded in a log file.
6. Any errors encountered are handled using exception handling.

## Project Structure
```
File-Cleanup-Automation/
│
├── file_cleanup.py
├── README.md
├── operations_log.txt
└── screenshots/
```

## Sample Output
```
Enter the folder path: D:\TestFolder

Renamed report.pdf -> File_1.pdf
Deleted empty file: temp.txt
Renamed image.jpg -> File_2.jpg

Automation completed successfully.
```

## Learning Outcomes
- Understanding file handling using the OS module.
- Implementing automation scripts in Python.
- Using exception handling for robust applications.
- Creating and maintaining log files.
- Managing project documentation using GitHub.

## Author
Sinchana L Gowda