# Event-Handling-Practice-Assignment

"" Event Handling Practice Assignment
Objective:

Create a webpage with various buttons. Write JavaScript code to add event listeners for click, mouseover, mouseout, and dblclick events on these buttons. Each event should trigger a different action, such as changing the button color, displaying a message, or hiding the button.

Requirements:

HTML Structure:

Create a basic webpage structure with several buttons.
Give each button a unique id or class for identification.

JavaScript Code:

Write functions to handle the following events:
click
mouseover
mouseout
dblclick
Add event listeners to each button to trigger the appropriate actions.

Actions to Implement:

click: Change the button color.
mouseover: Display a message near the button.
mouseout: Hide the displayed message.
dblclick: Hide the button.
Example Output:

After implementing the JavaScript code, interacting with the buttons should trigger the specified actions, demonstrating event handling.

HTML Structure:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Event Handling Practice</title>
    <style>
        .button {
            padding: 10px 20px;
            margin: 10px;
            font-size: 16px;
            cursor: pointer;
        }
        .message {
            display: none;
            margin-top: 5px;
            color: red;
        }
    </style>
</head>
<body>
    <h1>Event Handling Practice</h1>
    <button id="button1" class="button">Button 1</button>
    <div id="message1" class="message">Mouse over Button 1</div>

    <button id="button2" class="button">Button 2</button>
    <div id="message2" class="message">Mouse over Button 2</div>

    <button id="button3" class="button">Button 3</button>
    <div id="message3" class="message">Mouse over Button 3</div>

    <script src="script.js"></script>
</body>
</html>

JavaScript Code (script.js):

You have to implement ---

Explanation:
HTML Structure: The HTML file includes three buttons, each with an associated div to display a message. The buttons have unique ids for identification.
JavaScript Code:
changeColor: Changes the button color to light blue when clicked.
showMessage: Displays a message near the button when the mouse is over it.
hideMessage: Hides the message when the mouse is moved away from the button.
hideButton: Hides the button when double-clicked.
Event listeners are added to each button for the specified events (click, mouseover, mouseout, dblclick).

This assignment provides practice with adding event listeners and handling different types of events using JavaScript.

-------****--------
