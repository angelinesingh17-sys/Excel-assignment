📘 Overview

This Excel Practice Assignment is designed to help learners understand and apply commonly used Excel formulas and text functions. The exercises cover basic mathematical functions, logical functions, conditional calculations, and text manipulation techniques.

🎯 Learning Objectives

By completing this assignment, you will learn how to:

Perform basic calculations using Excel functions.
Analyze data using statistical functions.
Apply logical conditions with the IF function.
Use conditional aggregation functions.
Extract and manipulate text from cells.
📋 Functions Covered
1. SUM()

Adds a range of numbers.

Syntax:

=SUM(number1, [number2], ...)

Example:

=SUM(B2:B10)

Returns the total of values from cells B2 to B10.

2. COUNT()

Counts the number of cells containing numeric values.

Syntax:

=COUNT(value1, [value2], ...)

Example:

=COUNT(B2:B10)

Returns the count of numeric entries in the range.

3. AVERAGE()

Calculates the arithmetic mean of a range of numbers.

Syntax:

=AVERAGE(number1, [number2], ...)

Example:

=AVERAGE(B2:B10)

Returns the average value of the selected range.

4. MIN()

Returns the smallest value in a range.

Syntax:

=MIN(number1, [number2], ...)

Example:

=MIN(B2:B10)

Returns the minimum value.

5. MAX()

Returns the largest value in a range.

Syntax:

=MAX(number1, [number2], ...)

Example:

=MAX(B2:B10)

Returns the maximum value.

🔍 Logical Function
6. IF()

Performs a logical test and returns different values based on the result.

Syntax:

=IF(logical_test, value_if_true, value_if_false)

Example:

=IF(B2>=50,"Pass","Fail")

Returns "Pass" if the value in B2 is 50 or greater; otherwise returns "Fail".

📊 Conditional Functions
7. SUMIF()

Adds values that meet a specified condition.

Syntax:

=SUMIF(range, criteria, [sum_range])

Example:

=SUMIF(C2:C10,"Sales",B2:B10)

Adds values in B2:B10 where the corresponding cell in C2:C10 equals "Sales".

8. COUNTIF()

Counts cells that meet a specified condition.

Syntax:

=COUNTIF(range, criteria)

Example:

=COUNTIF(C2:C10,"Sales")

Counts the number of cells containing "Sales".

✍️ Text Functions
9. LEFT()

Extracts a specified number of characters from the beginning of a text string.

Syntax:

=LEFT(text, [num_chars])

Example:

=LEFT(A2,3)

Returns the first 3 characters from cell A2.

10. RIGHT()

Extracts a specified number of characters from the end of a text string.

Syntax:

=RIGHT(text, [num_chars])

Example:

=RIGHT(A2,4)

Returns the last 4 characters from cell A2.

11. MID()

Extracts a specific number of characters from the middle of a text string.

Syntax:

=MID(text, start_num, num_chars)

Example:

=MID(A2,3,5)

Returns 5 characters starting from the 3rd character in A2.

📝 Assignment Tasks
Create a dataset containing:
Employee Name
Department
Salary
Performance Score
Apply:
SUM() to calculate total salary.
COUNT() to count employees.
AVERAGE() to find average salary.
MIN() and MAX() to identify lowest and highest salaries.
Use:
IF() to classify employees as Eligible or Not Eligible based on performance score.
Apply:
SUMIF() to calculate total salary by department.
COUNTIF() to count employees in a specific department.
Use:
LEFT(), RIGHT(), and MID() to extract portions of employee IDs or names.
✅ Expected Outcome

After completing this assignment, you will be able to:

Perform mathematical and statistical calculations.
Apply logical decision-making formulas.
Generate conditional summaries.
Manipulate and extract text efficiently.
Build a strong foundation in Excel data analysis.
