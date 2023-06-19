# NET SALARY CALCULATOR

This form takes in two values; basic salary and benefits; and generates the individual's net salary.

## HTML code
### taking in salary and benefits values
Textboxes are created using <input> method in which the salary values are keyed in for evaluation.

### button to execute net salary evaluation
A button is created using <button> and is connected to the relative js function `calculateNetSalary()` through <button onclick = "">

## Javascript code
### declaring the function
In the script section, a function is created (same one mentioned in the button onclick section) in which the tasks to be executed on the keyed-in values are defined

### extracting value from the html form
The values entered in the html form are taken using     `getElementById()`. Since they are in string form, they are converted to numbers using `parseFloat()`. These values are then assigned to variables, eg; 'basicSalary' and 'benefits' for them to be acessed easily during calculation

### calculating deductions
Deductions are calculated usin the values of basic salary and benefits and used to finally calculate the net salary

### displaying net salary

The calculated deductions and net salary values are displayed using innerHTML to show within designated display paragraoh