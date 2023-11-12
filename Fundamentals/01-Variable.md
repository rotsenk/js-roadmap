# What is a variable?

Una variable nos permite almacenar datos de nuestros programas.

```html 
<button id="button_A">Press Me</button>
<h3 id="heading_A"></h3>
```
```js
// Get references to HTML elements
        var button = document.getElementById('button_A');
        var heading = document.getElementById('heading_A');

        // Add a click event listener to the button
        button.addEventListener('click', function() {
            // Change the text content of the h3 element
            heading.textContent = 'Button Pressed!';
        });
```

> Variables are used for various purposes in programming and web development, such as storing user input, performing calculations, controlling program flow, and interacting with web page elements (e.g., the DOM in web development) to create dynamic content.

# Declaring Variable
To use a variable, you've first go to create it - more accurately, we call this declaring the variable.

### features of a variable:
1. nombre
2. valor almacenado (tipo de dato)
3. Dirección de memoria

To do this, we type keyword let followed by the name you want to call you variable:

```js
var myName; 
let myAge;//más recomendada
```

Here we're creating two variables called `myName` and `myAge`.
Note: In JS, all code instructions should end with a semicolon ( ; ) - your code may work correctly for single lines, but probably won't when you are writting multiple lines of code together.
Try to get into the habit of including it.
