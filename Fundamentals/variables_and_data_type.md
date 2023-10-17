# JavaScript: Variables and Data Types

In JavaScript, variables and data types are fundamental concepts that play a crucial role in programming. Let's explore these topics in more detail:

## Variables and Their Declaration

Variables are used to store and manage data in JavaScript. They serve as containers for values. Variable declaration is the process of creating a variable and specifying its name.

- Variables can be declared using three different keywords: `let`, `var`, and `const`.
- `let` and `var` are used to declare variables with block scope and function scope, respectively.
- `const` is used for declaring constants, which cannot be reassigned after initialization.

## Data Types and Their Uses

JavaScript supports various data types that define the kind of data a variable can hold. Common data types include:

- **Number:** Represents numeric values, both integers and floating-point numbers.
- **String:** Represents textual data enclosed in single or double quotes.
- **Boolean:** Represents either `true` or `false`, used for logical operations.
- **Object:** A complex data type that can hold multiple key-value pairs.
- **Array:** A type of object used to store lists of values.
- **Null:** Represents an intentional absence of any object value.
- **Undefined:** Represents a variable that has been declared but not assigned a value.
- **Symbol:** A unique and immutable value used as object property keys.

## String with Template Literals

String manipulation is common in JavaScript. Template literals allow you to create strings with embedded expressions, making it easy to concatenate variables within strings using backticks (\`).

Example:
```javascript
const name = "John";
const age = 30;
const greeting = `My name is ${name} and I am ${age} years old.`;

