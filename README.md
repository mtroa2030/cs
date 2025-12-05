# Study Tracker
The Study Tracker is a simple Python command-line program designed to help you organize your school or study tasks. It allows you to record what you need to do, what subject it belongs to, and when it's due, all while giving you an easy way to keep track of which tasks you’ve already completed.

# Features
This program lets you add new tasks, list everything you need to work on, and mark tasks as done once you finish them. Everything is stored using basic Python lists, making the whole system lightweight and easy to understand. Since it runs entirely in the terminal, it’s perfect for beginners who want to learn how simple trackers or CRUD programs work.

# How It Works
The script uses four lists to store your data: one for the task names, one for their subjects, one for deadlines, and another to track whether each task is completed or not. These lists all share the same index positions, so each task’s details stay aligned. A menu loop controls the entire flow, allowing you to navigate between adding, viewing, and updating tasks.

# How to Run
To use this program, make sure Python 3 is installed on your system. Save the file as `study_tracker.py`, open your terminal, and run it using:

   python3 study_tracker.py

After that, you can choose options from the menu to manage your tasks.

# Example
===== STUDY TRACKER =====
1 - Add Task
2 - View Tasks
3 - Mark Task as Done
4 - Exit
Choose: 1

--- ADD TASK ---
Task name: Homework 3
Subject: Math
Deadline: Friday
Task added!

# Future Improvements
Some possible upgrades include saving tasks to a file so they persist after closing the program, adding editing or deleting options, sorting tasks by deadlines or subjects, switching to a class-based system, or even turning it into a GUI application later on.
