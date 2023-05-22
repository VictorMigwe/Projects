>- Name: Time Tracker
>- Version: 1.0
>- Author: Victor T. Migwe
>- Dependencies: Python 3.6 or later
>- Project Description: Time Tracking Application
>- Bugs: None known at this time.
>- License: This program is licensed under the MIT License.



# Time Tracking Application
The Time Tracking Application is a command-line Python program that allows users to track and manage tasks along with their elapsed times. It provides various functionalities such as;
Starting a task, stopping a task, displaying the task history, displaying the total completed time, and exporting the task history to a text file.

## Features

### `Start a Task`

-   Allows the user to start a new task by entering a task name.
-   Adds the task to the tasks dictionary with the current time as the start time.
-   If the task name already exists, it displays a message indicating that the task already exists.

### `Stop a Task`

-   Allows the user to stop a running task by entering the task name.
-   Calculates the elapsed time since the task was started.
-   Stores the task in the tasks dictionary as a tuple with the start and end times.
-   If the task name is not found or the task is already stopped, it displays an appropriate message.

### `Display Task History`

-   Displays the task history along with their respective elapsed times.
-   If a task is currently running, it displays "In progress" instead of the elapsed time.
-   If no tasks are tracked, it displays a message indicating that no tasks are tracked.

### `Display Total Completed Time`

-   Calculates and displays the total completed time across all the stopped tasks.
-   Ignores the running tasks and considers only the tasks that have been stopped.

### `Export Task History`

-   Allows the user to export the task history to a text file.
-   By default, the exported file is named "task\_history.txt" and has a .txt extension.
-   The user can specify a different filename during the export process.
-   The exported file includes the task history with their respective elapsed times.
-   If a task is currently running, it is indicated as "In progress" in the exported file.

### `Exit the Program`

-   Allows the user to exit the program gracefully.


## Usage

Run the program by executing the script. The main menu will be displayed with the available options. Enter the corresponding number for the desired action:

-   To `start a task`, choose option 1 and enter the task name.
-   To `stop a task`, choose option 2 and enter the task name.
-   To `display the task history`, choose option 3.
-   To `display the total completed time`, choose option 4.
-   To `export the task history`, choose option 5 and optionally enter a filename.
-   To `exit the program`, choose option 6.

## Dependencies

The Time Tracking Application requires the following dependencies:

-   Python 3.x
-   No additional external libraries or packages are required.


## Limitations

-   The Time Tracking Application runs in a single session and does not persist data across sessions. Once the program is closed, the task history is lost.
-   The elapsed time is calculated based on the system time, so it may not be precise in cases where the system time is adjusted or there are time discrepancies.
-   The program does not handle concurrent access or multiple users. It is designed for single-user usage.
-   The task history is stored in memory during the program execution. If the program terminates unexpectedly, the task history will be lost.

## Conclusion

The Time Tracking Application provides a simple and convenient way to track and manage tasks along with their elapsed times. Whether you need to monitor your work activities, track project durations, or analyze your productivity, this application can assist you in keeping organized records.