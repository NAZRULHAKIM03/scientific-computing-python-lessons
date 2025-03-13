Luhn Algorithm - Card Number Validation

This project implements the Luhn Algorithm, a simple checksum formula used to validate various identification numbers, primarily credit card numbers.

How It Works
	•	The program removes spaces and dashes from the card number.
	•	It reverses the number and applies the Luhn formula:
	•	Doubles every second digit from the right.
	•	If doubling results in two digits (≥10), sum them together.
	•	Adds all the digits and checks if the total is divisible by 10.
	•	Prints “VALID!” if the card number is valid, otherwise “INVALID!”.

