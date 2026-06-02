README – Excel Formula Functions Workbook
Overview

This workbook demonstrates the usage of commonly used Microsoft Excel formulas for performing calculations, logical operations, text manipulation, and data analysis. Each worksheet contains sample data and examples to help users understand how these functions work in real-world scenarios.

Functions Covered
1. SUM()

Purpose: Adds all numbers in a specified range.

Syntax:

=SUM(range)

Example:

=SUM(B2:B10)
2. MIN()

Purpose: Returns the smallest value in a range.

Syntax:

=MIN(range)

Example:

=MIN(B2:B10)
3. MAX()

Purpose: Returns the largest value in a range.

Syntax:

=MAX(range)

Example:

=MAX(B2:B10)
4. COUNT()

Purpose: Counts the number of cells containing numeric values.

Syntax:

=COUNT(range)

Example:

=COUNT(B2:B10)
5. AVERAGE()

Purpose: Calculates the arithmetic mean of a set of numbers.

Syntax:

=AVERAGE(range)

Example:

=AVERAGE(B2:B10)
6. AVERAGEIF()

Purpose: Calculates the average of cells that meet a specified condition.

Syntax:

=AVERAGEIF(range, criteria, average_range)

Example:

=AVERAGEIF(A2:A10,"Sales",B2:B10)
7. AVERAGEIFS()

Purpose: Calculates the average of cells that satisfy multiple conditions.

Syntax:

=AVERAGEIFS(average_range, criteria_range1, criteria1, ...)

Example:

=AVERAGEIFS(C2:C20,A2:A20,"Sales",B2:B20,"East")
8. IF()

Purpose: Performs a logical test and returns one value if TRUE and another if FALSE.

Syntax:

=IF(logical_test, value_if_true, value_if_false)

Example:

=IF(B2>=50,"Pass","Fail")
9. SUMIF()

Purpose: Adds values that meet a specific condition.

Syntax:

=SUMIF(range, criteria, sum_range)

Example:

=SUMIF(A2:A10,"Sales",B2:B10)
10. COUNTIF()

Purpose: Counts cells that meet a specified condition.

Syntax:

=COUNTIF(range, criteria)

Example:

=COUNTIF(A2:A10,"Sales")
11. RIGHT()

Purpose: Extracts a specified number of characters from the right side of a text string.

Syntax:

=RIGHT(text, num_chars)

Example:

=RIGHT(A2,4)
12. UPPER()

Purpose: Converts text to uppercase.

Syntax:

=UPPER(text)

Example:

=UPPER(A2)
13. LOWER()

Purpose: Converts text to lowercase.

Syntax:

=LOWER(text)

Example:

=LOWER(A2)
Sample Data
Department	Region	Sales	Employee ID
Sales	East	5000	EMP1001
Sales	West	4500	EMP1002
HR	East	3000	EMP1003
Finance	South	5500	EMP1004
Sample Formulas
=SUM(C2:C5)
=MIN(C2:C5)
=MAX(C2:C5)
=COUNT(C2:C5)
=AVERAGE(C2:C5)
=AVERAGEIF(A2:A5,"Sales",C2:C5)
=AVERAGEIFS(C2:C5,A2:A5,"Sales",B2:B5,"East")
=IF(C2>4000,"High","Low")
=SUMIF(A2:A5,"Sales",C2:C5)
=COUNTIF(A2:A5,"Sales")
=RIGHT(D2,4)
=UPPER(A2)
=LOWER(A2)
Learning Objectives

By using this workbook, users will be able to:

Perform basic mathematical calculations.
Analyze data using conditional functions.
Apply logical tests with IF statements.
Count and summarize data based on criteria.
Manipulate text using string functions.
Improve spreadsheet productivity and reporting skills.
Requirements
Microsoft Excel 2016 or later
Basic understanding of spreadsheet concepts
Version Information

Workbook Name: Excel Formula Functions Practice Workbook
Version: 1.0
Purpose: Learning and demonstration of fundamental Excel formulas
Last Updated: February 2026

Notes
All formulas are provided with sample data for easy understanding.
Users are encouraged to modify the sample data and experiment with different inputs to observe formula behavior.
Ensure that cell references are updated appropriately when applying formulas to different datasets.
