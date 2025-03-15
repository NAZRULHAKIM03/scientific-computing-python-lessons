Case Converter

A simple Python program that converts strings from Camel Case or Pascal Case into Snake Case.

Features
    • Converts Pascal Case (e.g., IAmAPascalCasedString) to Snake Case (i_am_a_pascal_cased_string)
    • Converts Camel Case (e.g., iAmACamelCasedString) to Snake Case (i_am_a_camel_cased_string)
    • Uses List Comprehension for a concise implementation

How It Works

The program iterates through each character in the input string. If the character is uppercase, it is converted to lowercase and prefixed with an underscore. The resulting string is then cleaned to remove any leading underscores.
