Week 1 Code Challenge, By : Gabriel Mwenda

Student-Grade-Generator;
This program is a simple student grade calculator written in HTML, CSS, and JavaScript. It allows the user to input their marks (score) between 0 and 100 and calculates their corresponding grade. Here's how it works:

First, the HTML code defines a form with a label and input field for the user to enter their marks. The form also includes a submit button and an empty paragraph element for the output.

Next, the CSS code styles the page with a basic layout and design, including font style and color, input field style, and button style.

The JavaScript code contains an event listener that listens for the submit event on the form. When the user clicks the submit button, the event listener triggers a callback function that does the following:

Prevents the default form submission behavior using event.preventDefault().
Retrieves the value of the marks input field using document.querySelector("#marks").value.
Initializes a variable called "grade" to store the calculated grade.
Uses a series of conditional statements to calculate the grade based on the marks value. If the marks value is greater than 79, the grade is set to "A", if the marks value is between 60 and 79, the grade is set to "B", and so on.
Updates the output paragraph element with the calculated grade using output.textContent.
When the user submits the form, the program calculates the corresponding grade based on their input and displays it on the page.

Overall, this program demonstrates how HTML, CSS, and JavaScript can be used together to create interactive web pages.





Speed-detector;
This program is a simple speeding ticket calculator. When a user enters a car's speed in km/h and clicks the "Calculate" button, the program will determine the number of points that the driver will receive on their license based on their speed.

The HTML page contains a form with a label and an input field for the car's speed. There is also a button that calls the JavaScript function "calculate" when clicked.

The JavaScript function "calculate" retrieves the speed entered by the user from the input field using the getElementById method. It then checks the speed against the speed limit of 70 km/h. If the speed is less than 70 km/h, the function will display "Ok" in the result paragraph. If the speed is greater than or equal to 70 km/h, the function calculates the number of points the driver will receive on their license using the formula Math.floor((speed - 70) / 5). If the number of points is greater than 12, the function will display "License suspended" in the result paragraph. Otherwise, it will display "Points: X" where X is the number of points the driver will receive.

If the user enters an invalid speed, the function will display an error message in the "error" paragraph.





Net-salary-calculator;
The program takes the user's input for their basic salary and benefits and then calculates the Payee Tax, NHIF Deduction, NSSF Deduction, and Net Salary based on the provided tax and deduction rates.

First, the program retrieves the values for the basic salary and benefits using document.getElementById("basic-salary").value and document.getElementById("benefits").value.

The Payee Tax calculation is done using a series of conditional statements that compare the taxable income (i.e. the basic salary plus benefits) to the tax brackets listed in the link provided earlier. If the taxable income is below KES 24,000, there is no Payee Tax. If the taxable income falls within a certain range, the Payee Tax is calculated using the corresponding tax rate.

The NHIF Deduction is calculated in a similar way, using a series of conditional statements that compare the taxable income to the NHIF rate brackets provided in the link. If the taxable income falls within a certain range, the NHIF Deduction is calculated using the corresponding rate.

The NSSF Deduction is calculated as 12% of the basic salary, up to a maximum of KES 2,160.

Finally, the Net Salary is calculated as the sum of the basic salary and benefits, minus the Payee Tax, NHIF Deduction, and NSSF Deduction.

The program then displays the results using document.getElementById() and .value.
