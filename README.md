# JavaScript

**What is JavaScript?**
JavaScript was first created to make web page only, latter on by adding new feature JS is used for lot more than developing web-page.
JavaScript is multi-paradigm language. You can write procedural, class-oriented, or FP-style code, and you can make those decisions on a line-by-line basis instead of being forced into an all-or-nothing choice.

## JavaScript Fundamentals 
The most fundamental unit of information in a program is a value. Values are data. They're how the program maintains state. Values come in two forms in JS: **primitive** and **object**.

1. **Primitive Data type**:
   1. *Number* (`var x= 420 // x is number`) Beside *number*, there are so called "special numberic value":
      * NaN - NOt a number.
      * Infinite and -Infinite 
   1. *String* (`var full_name="Geroge Hotz" //full_name is a string` )
   1. *Boolean* (ture/false)
   1. *Null* - For unknow value
   1. *Undefined* - For unassinged value

1. **Object**
   * Array
   * Date
   * Class
   * Error and *many more*.
   
### Different ways to get Output.
* `console.log("Hello, world!");`

*  `alert("Hellow, world!");`

### Different ways to get input.
* *Prompt*
   ```js
   var result= prompt(title,default)
   //title - The text to show the visitor.
   //default - An optional second parameter, the initial value for the input field.
   ```
* *Confirm*
   ```js
   result=confirm(question)
   //The function confirm shows a modal window with a question and two buttons: OK and Cancel.
   //The result is true if OK is pressed and false otherwise.
   ```
### Value Type Determination

For distinguishing values, the `typeof` operator tells you its built-in type, if primitive, or `"object"` otherwise:

```js
typeof 420;                  // "number"
typeof "George Hotz";        // "string"
typeof true;                // "boolean"
typeof undefined;           // "undefined"
typeof null;                // "object" Null is not an object its a bug.
typeof { "a": 1 };          // "object"
typeof [1,2,3];             // "object"
typeof function hello(){};  // "function"
```
### Function
Function declaration:
```js
function showMessage() {
  alert( 'Hello everyone!' );
}
```


