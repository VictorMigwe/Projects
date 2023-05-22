# Project Specifications
The objective of this project is to design and implement a time tracking application using Python. The application allows users to track the time spent on various tasks and provides functionalities to start a task, stop a task, display task history, and display the total completed time.

# Project Requirements
>1. Implement a `start_task()` function that prompts the user to enter the task name and starts tracking the time for that task.

>2. Implement a `stop_task()` function that prompts the user to enter the task name and stops tracking the time for that task. The function should calculate the duration of the task and store it.

>3. Implement a `display_task_history()` function that displays the task history, including the task name and the time spent for each task. The function should differentiate between currently running tasks and completed tasks.

>4. Implement a `display_total_completed_time()` function that calculates and displays the total completed time spent on all tasks.

>5. Create a user-friendly main menu that allows users to interact with the application. The main menu should provide options to start a task, stop a task, display task history, display the total completed time, and exit the program.


# Starter Code
```python
import time

def start_task(tasks):
    # -----
    # TO DO
    # -----

def stop_task(tasks):
    # -----
    # TO DO
    # -----

def display_task_history(tasks):
    if tasks:
        print("Task History:")
        for task_name, task_info in tasks.items():
            if isinstance(task_info, float):  # Check if task is currently running
                # -----
                # TO DO
                # -----
            else:
                # -----
                # TO DO
                # -----
    else:
        print("No tasks tracked.")

def display_total_completed_time(tasks):
    total_time = 0
    for task_info in tasks.values():
        if isinstance(task_info, tuple):  # Check if task is stopped
            # -----
            # TO DO
            # -----
    print(f"Total Completed Time: {round(total_time, 2)} seconds")

def main_menu(tasks):
    while True:
        # -----
        # TO DO
        # -----
        print()

def exit_program():
    print("Exiting the program. Goodbye!")
    exit()

def run_program():
    tasks = {}
    main_menu(tasks)

run_program()
```