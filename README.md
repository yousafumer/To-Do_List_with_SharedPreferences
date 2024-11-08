# To-Do List App with Persistent Storage
This Flutter app allows users to create, update, and delete tasks in a to-do list. The tasks are saved locally using the SharedPreferences package, ensuring that the data persists even after the app is closed and reopened.

# Features
Add tasks with the ability to toggle task completion (mark tasks as completed).
Delete tasks from the list.
The app uses SharedPreferences to save tasks locally on the device.
Each task's completion status is stored and reflected when reopening the app.
Getting Started
# Prerequisites
Flutter SDK
SharedPreferences package for local storage.
Installation
Clone or download the project:

Download the project as a zip file and extract it.
Or, clone the repository (if hosted on GitHub) using:
bash
# Copy code
git clone https://github.com/your-username/repository-name.git
Navigate to the project folder:

bash
# Copy code
cd your-project-folder
Install dependencies: Run the following command in the terminal to get all required packages:

bash
Copy code
flutter pub get
# Running the App
To run the app on an emulator or connected device, use the following command:

bash
 # Copy code
flutter run
 # File Structure
main.dart: The main entry point of the app which sets up the home screen with ToDoScreen.
task_model.dart: Defines the Task model used to store task details and convert tasks to/from a map format for persistence.
todo_screen.dart: The screen that displays the to-do list, allows adding, deleting, and marking tasks as completed. It handles all user interactions and data persistence.
#  Dependencies
shared_preferences: Used to store the task data persistently on the device.
Usage
Add a task: Enter a task in the input field and press the add button.
Mark a task as completed: Click the checkbox next to a task to toggle its completion status.
Delete a task: Click the delete icon next to a task to remove it from the list.
The tasks are automatically saved to local storage, so they persist even when the app is restarted.
# Additional Notes
The app uses local storage to save tasks, making it useful even in offline mode.
You can manage the task list without requiring a backend server.
