# Loyola COMP 271 Lab 0

*Group activity*

## Functional requirements

Recurring rainfall calculation: Design a program called Rainfall that reads a list of numbers from the standard input (console) representing daily rainfall amounts as entered by a user. Produce the average of the non-negative values in the list up to *end of file (EOF)* as discussed in class. There may be negative numbers in the list, but the program should ignore them.

## Nonfunctional requirements

- Performance: For each additional input item, the program should produce a small, finite number of steps.
- Scalability: The program should handle arbitrarily large input sequences.
- Testability: The program should support automatic testing (without, say, the user entering any data or reading any data from an external file). (This is not required for this lab, but you should give it some initial thought.)

## Reflection

For each functional and nonfunctional requirements, what are one or more design or implementation consequences of the requirement?

What additional changes would you need to make to enable automatic testing for your code? At least how many test cases should you have, and which ones?

(Keep your reflection brief and at a high, conceptual level.)

## Submission

Add a readme file including your reflection and any other thoughts. Submit via Repl.it as discussed in class.

# Grading (total 5 points)

-    1 submission via Replit
-    1 correct average calculation for one or more inputs
-    0.5 empty output (rather than NaN or error) for empty input
-    0.5 detect EOF (rather than specific sentinel value) following Scanner-based idiom
-    0.5 input can have zero or more double values on each line
-    0.5 good coding style (indentation, use of final everywhere except when a variable has to be updated one or more times)
-    1 meaningful reflection (three or more sentences) preferably in readme file
