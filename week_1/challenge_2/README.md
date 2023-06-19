# SPPEED CALCULATOR

This form takes in value of the speed and evaluates whether it is above the speed limit or not.

## HTML code
### taking in speed value
A textbox is created using <input> method in which the driver keys in the car speed for evaluation.

### button to execute speed evaluation
A button is created using <button> and is connected to the relative js function `calculateSpeed()` through <button onclick = "">

## Javascript code
### declaring the function
In the script section, a function is created (same one mentioned in the button onclick section) in which the tasks to be executed on the keyed-in values are defined

### extracting value from the html form
The value entered in the html form is taken using     `getElementById()`. Since it is in string form, it is converted to integer form using `parseInt()`. The value is then assigned to a variable, eg; 'speed` to be acessed easily during calculation

### calculating speed
Using if statement, it checks the speed and if it is within speed limit an `Ok` message is displayed.
If speed is above the limit, points are given to the driver for every 5kph the speed is above the limit
When points are greater than 12 the message `license suspended` is shown

