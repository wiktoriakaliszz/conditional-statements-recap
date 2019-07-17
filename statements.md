# Conditional Statements
![](cond.png)

In this guide, we’ll be covering the following concepts:
* `if`, `else if`, and `else` statements
* comparison operators
* logical operators
* truthy vs falsy values
* the `switch` statement

## The `if` Keyword
We often perform a task based on a condition. For example, if the weather is nice today, then we will go outside. If the alarm clock rings, then we’ll shut it off. If we’re tired, then we’ll go to sleep.

```js
if (hungry) {
    console.log('Time to eat!')
}
```

The `if` statement is composed of:
* the `if` keyword followed by a set of **parentheses** `()` which is followed by a code block, or block statement, indicated by a set of **curly braces** `{}`
* inside the parentheses `()`, a **condition** is provided that evaluates to true or false
* if the condition evaluates to **true**, the code inside the curly braces `{}` **runs**, or **executes**
* if the condition evaluates to **false**, the block **won’t execute**!

## `If... Else` Statements
An `else` statement must be paired with an `if` statement, and together they make an `if...else` statement.

```js
if (sleepy) {
    console.log('Time to go to sleep!');
} else {
    console.log('One more episode!');
}
```
 It's pretty simple, think about it that way - if the condition inside your code block is true, execute the block. If it equals to false, do not run the code and replace it with something else!

 [Here is a cool tutorial for y'all](https://youtu.be/N4V0FZASK60)

 ## Comparison Operators
* less than: `<`
* greater than: `>`
* less than or equal to: `<=`
* greater than or equal to: `>=`
* is equal to: `===`
* is **not** equal to: `!==`

## Logical Operators
* the and operator `&&`
* the or operator `||`
* the not operator, otherwise known as the bang operator `!`

## Truthy vs Falsy
The following values are **always falsy**:

* `false`
* `0`
* `' '` or `" "` (empty string)
* `null`
* `undefined`
* `NaN` (not a number)

Everything else is **truthy**. That includes:

* `'0'` (a string containing a single zero)
* `'false'` (a string containing the text “false”)
* `[ ]` (an empty array)
* `{ }` (an empty object)
* `function(){}` (an empty function)

[Another one!](https://youtu.be/dQw4w9WgXcQ)

## The Ternary Operator
This operator is frequently used as a shortcut for the `if...else` statement.

```js
let isNightTime = true;

if (isNightTime) {
  console.log('Turn on the lights!');
} else {
  console.log('Turn off the lights!');
}
```
Using the ternary operator, we shorten our code into:

```js
isNightTime ? console.log('Turn on the lights!') : console.log('Turn off the lights!');
```

* the condition (`isNightTime`) is provided before the `?`
* two expressions follow the `?` and are separated by a colon `:`


## `Else If` Statements
Want more conditions to your `if...else`? Add as many `else if` statements as you’d like.

The `else if` statement always comes **after** the `if` statement and **before** the `else` statement and also takes a condition. 

```js
let stopLight = 'yellow';

if (stopLight === 'red') {
  console.log('Stop!');
} else if (stopLight === 'yellow') {
  console.log('Slow down.');
} else if (stopLight === 'green') {
  console.log('Go!');
} else {
  console.log('Caution, unknown!');
}
```
`if / else if / else` statements are always read from top to bottom!

[Another one!](https://youtu.be/ZPpXJ3dk9gE)

## The `switch` Keyword
A `switch` statement provides an alternative syntax that is easier to read and write.

```js
let fromSoft = 'Dark Souls';

switch (fromSoft) {
  case 'Bloodborne':
    console.log('This game costs $40');
    break;
  case 'Dark Souls':
    console.log('This game costs $20');
    break;
  case 'Dark Souls 2':
    console.log('This game costs $25');
    break;
  default:
    console.log('Not a FromSoft game');
    break;
}
```
* multiple `case`s
* `break` stops the remaining `case`s from being checked
* at the end always a `default` statement (none of the cases === true, the code in the `default` statement will run)

[The last one (for real)](https://youtu.be/UeXDAu7SdmY)









 




