Random Password Generator 🔐
  A simple JavaScript program that generates secure random passwords with customizable options including lowercase, uppercase, numbers, and symbols.

Features
 1. Generate passwords of any length
 2. Optionally include:
    Lowercase letters
    Uppercase letters
    Numbers
    Symbols (!@#$%^&*()_+-=)
 3. Ensures at least one character type is selected
 4. Easy to use and fully customizable via code

How It Works
  The generator creates a password by:
    1. Selecting the allowed character sets based on user preferences.
    2. Randomly picking characters from the combined set.
    3. Returning a password of the requested length.
  It also validates input:
    Password length must be at least 1
    At least one character set must be selected

Usage
  1. Clone or download this repository:
    git clone <your-repo-link>

  2. Open index.js in your browser console or run it in Node.js.

  3. Adjust the options:
    passwordLength → Length of the password
    includeLowercase → true/false
    includeUppercase → true/false
    includeNumbers → true/false
    includeSymbols → true/false

  4. Run the script to generate a random password.
