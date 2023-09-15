# Age-calculator

This repository contains a simple Age Calculator web application. Users can input their birthdate and calculate their current age using this application. Below are the key files and their descriptions:

Files Included
index.html: This file contains the HTML structure of the Age Calculator web application. It includes input fields for date selection and a button to trigger the age calculation.

style.css: This file contains the CSS styles for styling the Age Calculator web application. It defines the layout, colors, and appearance of the application's elements.

script.js: This JavaScript file is responsible for handling user interactions and performing the age calculation based on the selected date of birth.

HTML Structure
html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Meta tags and title -->
</head>
<body>
    <div class="container">
        <div class="calculator">
            <h1>Age Calculator <br><span>App</span></h1>
            <div class="input-box">
                <input type="date" id="date">
                <button onClick="calculateAge()">Calculate</button>
            </div>
            <p id="result"></p>
        </div>
    </div>
</body>
<script src="./script.js"></script>
</html>
CSS Styling
The style.css file contains CSS rules for styling the application's elements. It defines the layout, colors, and fonts used in the application. Here are some key styling points:

Setting global styles for all elements.
Styling the container and calculator sections.
Defining the appearance of the input box and button.
Styling the result display.
JavaScript Logic
The script.js file contains JavaScript code to handle user interactions and calculate the age based on the input date of birth. The calculateAge() function is called when the "Calculate" button is clicked, and it updates the result in the HTML.

Feel free to customize and enhance this Age Calculator as needed for your project. Happy coding!
