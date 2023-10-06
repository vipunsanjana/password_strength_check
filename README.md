# Password Strength Checker



This is a simple web-based password strength checker tool built with HTML, CSS, and JavaScript. It allows users to check the strength of their passwords and provides feedback on how secure or weak their passwords are.

## Features

- Password strength evaluation: Determine the strength of a password based on various criteria.
- Real-time feedback: Instantly update the password strength as the user types.
- User-friendly interface: A clean and intuitive design for easy use.
- Customizable criteria: You can easily customize the criteria for password strength according to your requirements.

## Usage

1. Clone or download this repository to your local machine.
2. Open the `index.html` file in your web browser.
3. Enter your password in the input field.
4. The password strength will be evaluated and displayed on the screen in real-time.

## Customization

You can customize the criteria for password strength by modifying the JavaScript code in the `script.js` file. Adjust the rules and scoring as needed for your specific use case.

```javascript
// Modify the password strength rules here
const rules = {
  minLength: 8,          // Minimum password length
  minUpperCase: 1,      // Minimum uppercase letters
  minLowerCase: 1,      // Minimum lowercase letters
  minNumbers: 1,        // Minimum numbers
  minSpecialChars: 1,   // Minimum special characters
};
