# Multiplication-Table-from-1-to-10
Write a program print the multiplication table from 1 to 10 with c++

PrintTableHeader Function:
This function prints a title for the multiplication table and then iterates from 1 to 10 to print column headers. It also prints a long separator line to distinguish the header from the table body.
ColumSperator Function:
This helper function returns a string that serves as a separator between the row number and the multiplication values. The spacing is adjusted depending on whether the row number is a single-digit or two-digit number.
PrintMultiplicationTable Function:
This function first calls PrintTableHeader() to output the header. It then iterates over each row (1 to 10) and within each row, iterates over each column (1 to 10) to calculate and print the product. After printing each row, it moves to a new line.
Main Function:
The main() function is the entry point of the program. It simply calls PrintMultiplicationTable() to execute the main functionality and returns 0, indicating that the program has run successfully.
