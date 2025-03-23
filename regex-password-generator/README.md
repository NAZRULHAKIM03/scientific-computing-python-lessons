Password Generator

A simple Python program that generates strong passwords while ensuring they meet specific security requirements.

Features
    • Generates a random password of a specified length
    • Ensures the password contains at least one digit, one special character, one uppercase letter, and one lowercase letter
    • Uses Regular Expressions to validate the password format
    • Utilizes the `secrets` module for secure randomization

How It Works

The program randomly selects characters from a mix of uppercase letters, lowercase letters, digits, and special symbols. It then checks if the generated password meets all security constraints using Regular Expressions. If not, it regenerates a new password until a valid one is found.
