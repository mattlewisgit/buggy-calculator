Calculator available at: https://mattlewisgit.github.io/buggy-calculator/

User Story

Title: Web Calculator

Description:
As a kingfisher user, I want to perform basic arithmetic operations (addition, subtraction, multiplication, division) using a web-based calculator so that I can quickly calculate numbers in my browser.

Acceptance Criteria

1) Adding numbers together works as expected
2) Dividing numbers together works as expected
3) Multiplying numbers together works as expected
4) Subtracting numbers together works as expected
5) We do not see any unexpected behaviour from any other buttons
6) We expect the calculator to respond within milliseconds with the result of the calculation


Intended Bugs:

- Any calculation with decimal places will error.
- pressing = on an empty screen shows NaN/Error.
- pressing 9, actually inputs 6.
- Any expression with 3+ digit numbers takes 2 seconds to show the result
- Number 2 is slightly bigger than the rest.
- Dividing by Zero equals INFINITY
- You can select multiple decimal places
