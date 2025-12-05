# Study Tracker
The Study Tracker is a simple Python command-line program that helps you keep track of school or study tasks. You can record what you need to do, what subject it belongs to, and when it’s due, while also marking tasks as completed once you're done.

# Features
This tool allows you to add tasks, view all your current work, and mark tasks as done. The entire system uses basic Python lists, making it easy to understand and modify. Since it runs in the terminal, it's a great beginner-friendly example of how simple task managers work.

# How It Works
The script stores information in four parallel lists: one for task names, one for subjects, one for deadlines, and one for completion status. Each list index represents a single task. A menu loop handles navigation, letting you switch between adding, viewing, and completing tasks.

# How to Run
1. Make sure Python 3 is installed.
2. Save the file as `study_tracker.py`.
3. Run it using:

   python3 study_tracker.py

4. Follow the menu to add or manage tasks.

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
Future versions could save tasks to a file so they persist, allow editing or deleting tasks, sort by deadline or subject, replace lists with a Task class, or even include a GUI.

# License
Free to use and modify.
