# Character Case Converter in C

This C program takes a character as input from the user, and converts it between uppercase and lowercase using ASCII values.

## Features

- Converts a lowercase letter to uppercase.
- Converts an uppercase letter to lowercase.
- Uses ASCII values for the conversion.

## How it Works
- The program reads a character from the user and checks whether it is lowercase or uppercase
- The ASCII value for 'a' is 97, and for 'A' is 65. The difference between them is 97 - 65 = 32.
- If it's lowercase, it subtracts 32 from its ASCII value to convert it to uppercase. 
- If it's uppercase, it adds 32 to its ASCII value to convert it to lowercase.
