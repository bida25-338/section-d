
This project is a simple student grade management system developed using Python. It allows users to add students, record their grades, calculate their averages, and view their academic performance. It also provides an option to search for a student and update a grade when necessary.

The program uses functions to organise its different operations and a dictionary to store student information while the program is running.

## How the Program Works

When the program starts, the user is prompted to enter a student's name and grades for Biology, English, and Chemistry. Before the grades are stored, the program checks that each grade falls between 0 and 100.

Once a student has been added, the user can search for that student by name and view their recorded grades. If a grade needs to be changed, the program allows the user to select the subject and enter a new grade. The updated information is then displayed.

The program can also calculate each student's average and display a summary of the registered students and their results.

## Features of the program

* **Adding students:** Records a student's name and grades for the three subjects.
* **Grade validation:** Checks that grades are within the accepted range of 0 to 100.
* **Average calculation:** Calculates the average grade for each student.
* **Searching for students:** Finds a student by name and displays their grades.
* **Updating grades:** Allows the user to change a student's grade for a selected subject.
* **Student summary:** Displays the registered students and their average grades.
* **Basic error handling:** Handles searches for students or subjects that do not exist.

## Limitations

Student information is stored in a dictionary while the program is running. This means that the information is not permanently saved and will be lost when the program stops.



This project demonstrates the use of Python functions, dictionaries, loops, conditional statements, and basic exception handling to manage student grades. It provides a straightforward way to record, retrieve, and update student results.

