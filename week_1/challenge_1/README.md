# STUDENT GRADE CALCULATOR

This form takes in three values; entry exam, mid term exam and end term exam and generates the student's average term grade.

## HTML code
### taking in grade values
Textboxes are created using <input> method in which the student keys in the marks for evaluation.

### button to execute grade calculation
A button ix created using <button> and is connected to the relative js function `calculateGrade()` through <button onclick = "">

## Javascript code
### declaring the function
In the script section, a function is created (same one mentioned in the button onclick section) in which the tasks to be executed on the keyed-in values are defined

### extracting value from the html form
The values entered in the html form are taken using     `getElementById()`. Since they are in string form, they are converted to numbers using `parseFloat()`. These values are then assigned to variables, eg; 'entryExam', 'midExam' and 'endExam' for them to be acessed easily during calculation

### assigning grades
When the total marks are calculated the grade is assigned according to the total marks value. This is done using the if statement, where a variable `grade` is assigned a specific string depending on what value category the total marks fall in

### displaying grade evaluation

Using the if statement, the form will show an error message if any input field is empty. If all are filled, then the calculated grades are displayed within the paragraph created for displaying 
