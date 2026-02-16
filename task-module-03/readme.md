# Module 03: Interactive Logic
# OBJECTIVE: JavaScript Basics and User Interaction

## 1. Define JavaScript

JavaScript is a programming language used to make web pages interactive and dynamic. While HTML creates the structure of a webpage and CSS designs its appearance, JavaScript adds behavior and logic.

With JavaScript, a webpage can respond to user actions such as clicking a button, typing in a form, or moving the mouse. It can show messages, change content, update styles, validate forms, and even communicate with servers.

In simple terms, JavaScript makes a webpage “alive.” Without JavaScript, a website would only display static content. With JavaScript, the page can react and change based on user interaction.

## 2. The Big Three (HTML, CSS, and JavaScript)

HTML, CSS, and JavaScript work together to build a complete website.

- HTML is used to create the structure of a webpage. It defines elements such as headings, paragraphs, buttons, and images.

- CSS is used to style the webpage. It controls colors, fonts, spacing, alignment, and layout.

- JavaScript is used to add logic and interaction. It allows the page to respond to user actions and change content dynamically.

A simple comparison:

- HTML builds the content.

- CSS designs the content.

- JavaScript controls the behavior of the content.

- All three are essential for modern web development.

## 4. Logic Challenge (JavaScript Behavior)

When the user clicks the button:

1. An alert message appears saying “Button Clicked!”

2. The paragraph text changes from “Hello World” to “You clicked the button!”

3. The paragraph’s text color becomes white and the background color becomes blue.

This interaction is controlled using JavaScript.

## 5. Code Explanation

Below is a simple explanation of each part of the JavaScript code:

`function changeContent() {`


This line defines a function named `changeContent`. A function is a block of code that runs when it is called.

`alert("Button Clicked!");`


The `alert()` function displays a popup message on the screen. It shows a message when the button is clicked.

`var paragraph = document.getElementById("text");`


This line selects the paragraph element using its ID (`text`). The `document.getElementById()` method finds the element inside the webpage. The selected element is stored in a variable named paragraph.

`paragraph.innerHTML = "You clicked the button!";`


The `innerHTML` property changes the text inside the paragraph. After clicking the button, the text is updated.

```
 paragraph.style.color = "white";
 paragraph.style.backgroundColor = "blue"; 
```


These lines change the style of the paragraph. The text color becomes white, and the background color becomes blue. The style property is used to modify CSS using JavaScript.

Finally, the function ends with:

` } `


The button uses this line:

`<button onclick="changeContent()">Click Me</button>`


The `onclick` attribute calls the `changeContent()` function when the button is pressed. This connects the button with the JavaScript logic.

## Conclusion

JavaScript plays an important role in web development by adding interactivity and dynamic behavior to web pages. In this task, a simple button click event was used to display a message, change text content, and modify styles. This example demonstrates how JavaScript can respond to user actions and update a webpage instantly.