Programming test

Build a calculator that can show the history of operations.
The user should be able to perform the four most common arithmetic operations (addition, subtraction, multiplication and division) on the calculator app by constructing a valid expression using the input buttons, and have the result displayed on the screen. Examples of valid expressions are shown below:
12 + 5 
8.5 / 4
8% * 2
-16 - 6
Each number the user clicks is shown on the screen of the calculator (it is not mandatory to show the entire expression) and when clicking the equal button, the result is calculated.
The user can also visualize the ‘History’ of operations: a list of all expressions calculated until now. For the operations shown above, the history would be:
12 + 5 = 15
8.5 / 4 = 2.125
8% * 2 = 0.16
-16 - 6 = -22
A basic react/nextjs project is already created for you. You can run it with:
npm run dev
The result app should comprehend:
1.	All react components needed to create the calculator.
2.	Css files for the style (you can optionally use css modules).
3.	Arithmetic operations (addition, subtraction, multiplication and division).
4.	(Optional) Percentage, change of sign and cancel.
5.	An api call to calculate the result of an operation (there is an example of an api in the project that you can reach at “http://localhost:3000/api/hello”).
6.	Functionality to show / hide the history of operations.
