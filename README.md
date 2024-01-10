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
