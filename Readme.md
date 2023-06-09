# TaskMaster - Android App

TaskMaster is a simple task management Android application that allows  
users to create and view tasks. It's a project built for practicing  
Android development, and it will be improved and expanded over the  
course of development.

## Table of Contents

1. [Features](#features)
2. [Getting Started](#getting-started)
3. [Screenshots](#screenshots)
4. [Contributing](#contributing)
5. [License](#license)
6. [Change Log](#change-log)

## Features

- Users can create tasks with a title and description.
- The home screen provides a quick overview of the tasks.
- Users can navigate to an individual task screen from the main screen.

## Getting Started

1. Clone the repository

```zsh
git clone https://github.com/cfosprof/taskmaster.git  
```

2. Open the project in Android Studio.
3. Run the project on an emulator or a real device.

## Change Log And Screenshots

Screenshots of the application in action will be updated here.

<details markdown="block">
  <summary>2023-05-22</summary>  <img src="screenshots/home.png" alt="Home Screen" width="300">### Lab 26

- Set up the Android project and GitHub repository.

- Built the home screen with a placeholder "my tasks" image and buttons  
  for navigation.

- Implemented the "Add a Task" screen, allowing users to input task  
  details and display a confirmation message upon submission.

- Implemented the "All Tasks" screen with a placeholder image and a back  
  button.

- Added a screenshot of the home screen to the project documentation.

- Wrote unit tests for the custom helper methods.


![Lab26](screenshots/lab26.png)


</details>



## Lab 26

<details markdown="block">
  <summary>2023-05-22</summary>  <img src="screenshots/home.png" alt="Home Screen" width="300">

## Task list

1. Build the Homepage
   - [ ] Add a TextView to the top of the page and set its text to serve  
         as the heading of the homepage.
   - [ ] Add an ImageView below the heading and set a placeholder image  to mock the “my tasks” view.
   - [ ] Add two buttons at the bottom of the page. Label one button as  
         "Add Task" and the other as "All Tasks".


2. Create the Add a Task page
   - [ ] Create a new activity for the "Add a Task" functionality.
   - [ ] In the layout file of this new activity, add EditText views for  
         users to input task title and task body.
   - [ ] Add a Button view labeled as "Submit".
   - [ ] In the activity's Java file, add a click listener to the  
         "Submit" button that will display a Toast message or a TextView  
         saying "Submitted!" when the button is clicked.


3. Create the All Tasks page
   - [ ] Create a new activity for the "All Tasks" functionality.
   - [ ] In the layout file of this activity, add an ImageView and set a  
         placeholder image.
   - [ ] Add a Button view labeled as "Back". This button will navigate  
         back to the Homepage when clicked.


4. Documentation
   - [ ] Create a new directory in your project root directory named  
         `screenshots`.
   - [ ] Run  app on an emulator or real device, navigate to the  
         homepage, and take a screenshot.
   - [ ] Save this screenshot in the `screenshots` directory.
   - [ ] Add and commit this screenshot to Git repository, then  
         push the commit to GitHub.


5. Write unit tests
   - [ ] Identify any logic in  code that can be unit tested. This  
         can include custom helper methods or non-UI related logic.
   - [ ] Write unit tests for these pieces of logic using the JUnit  
         framework and the built-in testing capabilities of Android  
         Studio.

### Actual assignment

Submission Instructions  
Work in your new taskmaster repo.  
Work on a non-master branch and make commits appropriately.  
Update your README with your changes for today and screenshot of your work.  
Create a pull request to your master branch with your work for this lab.  
Submit the link to that pull request on Canvas. Add a comment with the amount of time you spent on this assignment.  
Grading Rubric  
2 pts Android application with 3 basic pages  
2 pts Form that displays a message on the “add task” page  
1 pts Overall functionality, lack of bugs  
1 pts README with description, screenshots, and daily change log

Feature Tasks  
Homepage  
The main page should be built out to match the wireframe. In particular, it should have a heading at the top of the page, an image to mock the “my tasks” view, and buttons at the bottom of the page to allow going to the “add tasks” and “all tasks” page.

Add a Task  
On the “Add a Task” page, allow users to type in details about a new task, specifically a title and a body. When users click the “submit” button, show a “submitted!” label on the page.

All Tasks  
The all tasks page should just be an image with a back button; it needs no functionality.

Documentation  
Create a directory called screenshots in the root of your project. Take a screenshot of the homepage you’ve created. Use markdown to render the screenshot in your README.


Testing  
In a future lecture, we’ll talk about how to test Android UI using Espresso. For now, ensure that you’re writing good unit tests for anything unit-testable in your code.

### Resources

[Canvas Assignment](https://canvas.instructure.com/courses/6504881/assignments/36513376)


</details>
