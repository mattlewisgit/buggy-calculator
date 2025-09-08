Calculator available at: https://mattlewisgit.github.io/buggy-calculator/

User Story

Title: Web Calculator

Description:
As a kingfisher user, I want to perform basic arithmetic operations (addition, subtraction, multiplication, division) using a web-based calculator so that I can quickly calculate numbers in my browser.

Acceptance Criteria

1) Adding numbers together works as expected
2) Dividing numbers together works as expected
3) Multipling numbers together works as expected
4) Subtracting numbers together works as expected
5) We do not see any unexpected behaviour from any other buttons
6) We expect the calculator to response within an acceptance timeframe


Intended Bugs:

- Calculator cannot handle floating numbers e.g. 2.999 + 1 = 2.99.
- pressing = on an empty screen shows NaN/Error.
- pressing equals takes adds 0.1 second to the time it takes to response.
