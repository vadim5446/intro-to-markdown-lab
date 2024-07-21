# intro-to-markdown-lab
# Writing a Function in JavaScript

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

## 1. Basic syntax
```javascript
const functionName = (params) => {
  // code to be executed
}
```
* **const**: const should be used whenever a function expression is assigned to a variable.
* __The function name__: The name you choose for the function.
* __Parameters__: Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.
* __The arrow syntax__: Indicates that this will be a function.
* __The body__: The statements that make up the function itself. Surrounded by curly braces.

**Example**:
```javascript
const greet = (name) => {
  console.log("Hello, " + name + "!");
}
```
> Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ). 

2. Calling a function

To execute the function, you _call_ or _invoke_ it by using its name followed by parentheses.

**Example**:
```javascript
greet('Alice'); // **Outputs**: Hello, Alice!
```
3. Return values

Functions can process data input and output a value using the _return_ keyword.

**Example**: 
```javascript
const addNums (numA, numB) => {
  return numA + numB
}
```
const total = addNums(2, 4);

console.log(total) // Expected value: 6
'''
For more information on functions and how they are used in JS, check out the MDN docs. 

[MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)

This text is **bold**. This text is also __bold__.

This text is in *italics*. This text is also in _italics_.

This text is ***bold and italicized***. This text is also ___bold and italicized___.

* Item 1
* Item 2
  * Subitem 2.1
  * Subitem 2.2
    * Subitem 2.2.1

1. First item
2. Second item
   1. Subitem 2.1
   2. Subitem 2.2

Use the `console.log()` function to print values to the console.

```javascript
const printItem = (item) => {
  console.log(item);
}
```
[Google](https://www.google.com)

This is [a reference][example].

[example]: http://www.example.com/

> This is a blockquote.

> First level of blockquote.
>> Nested blockquote.
>>> Another nested blockquote.

![some alt text](www.url_to_an_image.com/image)

![Computer with Code](https://images.unsplash.com/photo-1587620962725-abab7fe55159?auto=format&fit=crop&q=80&w=1631&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

![alt text](https://file%2B.vscode-resource.vscode-cdn.net/Users/vadim/Downloads/pexels-zeng-jinwen-679366437-20852606.jpg?version%3D1720711788203)

![mother and daughter in the winter](./assets/pexels-zeng-jinwen-679366437-20852606.jpg)

- [x] Task 1
- [ ] Task 2
- [ ] Task 3

This text has been ~~redacted~~. 
