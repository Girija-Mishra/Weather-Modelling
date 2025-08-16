🌦️ Quadratic Weather Modeling

This project demonstrates Quadratic Weather Modeling using Python.
The model assumes that temperature varies with time following a quadratic equation:

T(t)=a⋅t2+b⋅t+c

The implementation is done in three stages to show progressive development.

📂 Stages of Implementation
1️⃣ Stage 1 – Hardcoding / Keyboard Input

Variables a, b, c are either hard-coded in the script or taken from user input via keyboard.

The program calculates temperature values for t = 0 → 10 and plots the curve.

Useful for testing the formula quickly without external files.


2️⃣ Stage 2 – Single Set of Input (from File)

Coefficients a, b, c are stored in a CSV file (wea2.csv).

The program reads this single row of input using Pandas and generates the temperature curve.

Example wea2.csv:

a,b,c
2,-7,3


Output: A single quadratic curve plotted for given values of a, b, c.

3️⃣ Stage 3 – Multiple Sets of Inputs (from File)

The CSV file (wea.csv) contains multiple rows of coefficients.

The program reads all rows and plots multiple curves on the same graph for comparison.

Example wea.csv:

a,b,c
1,5,2
3,5,6
2,5,12
1,5,7
2,5,3
6,3,25
1,-7,13


Output: A multi-line plot showing how different quadratic equations affect temperature variation.
