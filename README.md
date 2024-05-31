Features:
Customizable Character: The character used to build the pyramid can be customized.
Row Count: The number of rows in the pyramid can be specified.
Inverted Option: The pyramid can be displayed in its standard orientation or inverted (upside-down).
Code Explanation:
Variables:

character: The character used to create the pyramid (e.g., "!").
count: The number of rows in the pyramid (e.g., 10).
rows: An array to store each row of the pyramid.
inverted: A boolean flag indicating whether the pyramid should be inverted (false by default).
Function:

padRow(rowNumber, rowCount): This function generates a single row of the pyramid. It pads the row with spaces to center the characters and returns the formatted row.
Main Loop:

A for loop iterates from 1 to count, generating each row of the pyramid.
Depending on the inverted flag, each row is either added to the beginning (unshift) or the end (push) of the rows array.
Result Construction:

A for loop concatenates all rows from the rows array into a single string, result, with newline characters separating each row.
Output:

The final pyramid shape is printed to the console.
