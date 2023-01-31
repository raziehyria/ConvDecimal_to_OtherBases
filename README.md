# ConvDecimal_to_OtherBases
Students need to understand what binary values are, and how to convert to other numerical bases.  This lab will demonstrate how to convert data.
C Programming Lab
Convert Decimal to Hex, Binary, and Octal
Programming guidelines
 Create a comment header, at the top of the document.
o It must contain your name, the course (and semester)
o brief description of what the program does.
 Line up your braces
 Indent properly
 Use meaningful variable names.
 Make the code readable.
Program Requirements
1. The project shall be called: “ConvDecimal_to_OtherBases”.
2. Input
a. Allow user to input an integer from 0 -> 2,000,000.
b. Validate the input.  If input is invalid, make them enter a value again 
(while), until they enter a valid value.
3. Processing
a. Use the Division method for converting Decimal to Binary, and 
Hexadecimal, and Octal.
i. Divide the quotient by 2 or 16 or 8, respectively.
ii. Get the remainder after dividing. Save the remainders.  They are 
the answer.
b. Display the answer with, the digits, in the proper order.
c. Loop and ask user to input another positive integer.
d. Stop looping and exit when the user enters “-1”.
e. Create a function (and a corresponding .h file) named ConvDecimal().
i. Make sure you store (and Add) this separate .cpp and .h file to your 
project.
f. You will create 1 function that will convert Decimal to all 3 other bases (2, 
16, and 8). You (the programmer) need to determine what the parameters 
should be for this function.
g. This function will return nothing.
4. Output
a. At beginning of the program, display some kind of welcome message, 
stating to the user what this program does.
b. When printing the results, display both the original decimal value and the 
calculated values. 
c. Display the output in a nice format.
5. Testing
a. Extensively test your program. Test with all type of integers values; valid 
and invalid data.