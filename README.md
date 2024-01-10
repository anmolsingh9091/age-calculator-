# age-calculator-
Certainly! This code creates a simple web page for an age calculator. Let's break it down:

HTML Structure:
<!DOCTYPE html>: Defines the document type and version of HTML.

<html lang="en">: Specifies the language of the document.

<head>: Contains meta-information about the document, such as the character encoding and the title.

<meta charset="UTF-8">: Sets the character encoding to UTF-8.
<title>CodePen - Age Calculator</title>: Sets the title of the webpage.
<link>: Loads external resources, in this case, a Google Fonts stylesheet and a custom style.css file.
<body>: Contains the visible content of the webpage.

<div class="container">: Acts as a container for the calculator.
<div class="input-wrapper">: Contains an input field for a date and a button to calculate the age.
<input type="date" id="date-input" />: Provides a date input field where the user can select a date.
<button id="calc-age-btn">Calculate</button>: A button triggering the age calculation.
<div class="output-wrapper">: Displays the calculated age in years, months, and days.
Three <div> elements, each containing:
<span id="years">-</span>: Placeholder for displaying the calculated years.
<p>Years</p>: Label for the years.
Similar placeholders for months and days.
<script src="./script.js"></script>: Links to an external JavaScript file (script.js) that handles the functionality of calculating the age based on the input date.

This CSS code provides the styling for the HTML structure you shared earlier, giving the age calculator a visually appealing layout. Here's a breakdown of what each section does:

General Styling:
*: Applies to all elements on the page and sets consistent properties.
padding: 0;, margin: 0;: Removes default padding and margins for all elements.
box-sizing: border-box;: Ensures padding and border sizes are included in the element's total width and height.
font-family: "Montserrat", sans-serif;: Sets the default font to Montserrat with a fallback to a generic sans-serif font.
Body Styling:
background: Sets a gradient background using linear-gradient from #eea6e5 to #ecf09d.
display: flex; justify-content: center; align-items: center;: Centers content both horizontally and vertically within the body.
min-height: 100vh;: Ensures the body takes at least the full height of the viewport.
margin: 0;: Removes any default margin on the body.
Container Styling:
.container: Styles the main container holding the calculator.
width: 90%; max-width: 420px;: Sets the container width to 90% of the parent or a maximum of 420px.
text-align: center; padding: 20px;: Centers the content within the container and adds padding.
background-color: rgba(255, 255, 255);: Sets a white background for the container.
border-radius: 6px;: Rounds the corners of the container.
box-shadow: Applies a shadow effect to the container.
Input and Button Styling:
.input-wrapper: Styles the wrapper containing the input and button.
input[type="date"], input, button: Styles the input fields and button.
font-weight: 500; border-radius: 5px; padding: 10px;: Sets common properties for these elements.
border: 1px solid #ccc; transition: border-color 0.3s;: Adds a transition effect on border color change.
Styling for :focus state of input elements and button hover state.
Output Styling:
.output-wrapper: Styles the wrapper for displaying the calculated age.
.output-wrapper div: Styles the individual output sections for years, months, and days.
flex-basis: calc(50% - 20px);: Sets the width of each output section to 50% with some margin.
background-color: rgba(255, 255, 255, 0.95);: Sets a slightly transparent white background.
border-radius: 10px; box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);: Adds rounded corners and a shadow effect.
text-align: center; padding: 20px; margin: 10px;: Centers text and adds padding/margin for each section.
Responsive Design:
@media (max-width: 768px): Applies styles for screens smaller than 768px width.
Adjustments made to .container and .output-wrapper div to ensure better responsiveness on smaller screens.
This CSS ensures a clean and responsive layout for the age calculator, making it visually appealing across different devices and screen sizes.
