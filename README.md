# Password Generator Website

## Project Overview

The Password Generator Website is a simple, user-friendly web application that allows users to generate strong and secure passwords. The application gives users the flexibility to customize the length of the password and include or exclude uppercase letters, numbers, and symbols according to their security needs. This project is a great example of integrating HTML, CSS, and JavaScript to create a functional and aesthetically pleasing web tool.

## Features

1. Customizable Password Length: Users can choose the desired number of characters (between 1 and 50) for the password.
2. Character Options: Users can include or exclude uppercase letters, numbers, and symbols based on their preferences.
3. Real-Time Updates: The password length can be adjusted using both a range slider and a numeric input, and the password is generated instantly upon form submission.
4. Responsive Design: The website is designed to be responsive and works well on different screen sizes.

## Project Structure
```bash
Password_Generator_Website/
├── index.html
├── styles.css
├── script.js
├── README.md
```

## Installation

To use the Password Generator Website, follow these steps:

1. Clone the Repository:
```bash
git clone https://github.com/skytruong90/Password_Generator_Website.git
```
2. Navigate to the Project Directory:
```bash
cd Password_Generator_Website
```
3. Open the index.html File:
Open the index.html file in your preferred web browser to view and use the password generator.

## How to Use

1. Open the Website:
Open the index.html file in your web browser. The password generator interface will be displayed.
2. Customize Password Settings:
 - Number of Characters: Use the slider or numeric input to select the desired password length (1-50 characters).
 - Include Uppercase: Check the box if you want to include uppercase letters in your password.
 - Include Numbers: Check the box if you want to include numbers.
 - Include Symbols: Check the box if you want to include special characters (symbols).
3. Generate Password:
Click the "Generate Password" button. The generated password will appear in the display area below the form.
4. Copy and Use Your Password:
You can now copy the generated password and use it for your desired purpose.

## Code Explanation

### HTML (index.html)
 - The HTML file structures the webpage and includes form elements like sliders, checkboxes, and buttons for user interaction.
 - The h1 element is used for the title, and the password is displayed in an h3 element.
 - The form captures user input for generating the password.
### CSS (styles.css)
 - The CSS file styles the page with a modern, clean look. It uses flexbox to center the content and provides a responsive design.
 - The .container class wraps the form and password display, with a dark theme and rounded borders for a sleek appearance.
 - The .btn class styles the button with a hover effect, enhancing user interaction.
### JavaScript (script.js)
 - The JavaScript file contains the logic for generating the password. It handles user input, processes the form, and displays the generated password.
 - The generatePassword function assembles the password based on user-selected options, using ASCII codes to include uppercase letters, numbers, and symbols.
 - Event listeners ensure that the password length slider and numeric input are synchronized and that the form submission triggers password generation.

## Future Enhancements

1. Copy to Clipboard: Add a button to allow users to easily copy the generated password to their clipboard.
2. Strength Indicator: Implement a password strength indicator that provides feedback on the strength of the generated password.
3. Save Passwords: Allow users to save generated passwords to a local file or database for future reference.
