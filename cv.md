## Andrey Kastruba
## Contacts
* Telegram: @duxa3
* Phone: +7-910-735-39-84

## Summary
I'm a student of RTU MIREA and beginner developer. I have been very motivated to learn JS, React, NodeJS for the last 2 years. I wish to start my career as Junior Web Developer next year.

## Languages and Tools
* Javascript
* React
* HTML
* CSS
* Sql

## Code Examples
```
function printResult() {
    let subResult = 0;
    let operand2 = 0;
    let index = 0;
    if (symbol == '+') {
        index = (result.innerHTML).indexOf('+');
        operand2 = parseInt((result.innerHTML).substring(index + 1), 2);
        subResult = equals + operand2;
    }
    else if (symbol == '-') {
        index = (result.innerHTML).indexOf('-');
        operand2 = parseInt((result.innerHTML).substring(index + 1), 2);
        subResult = equals - operand2;
    }
    else if (symbol == '*') {
        index = (result.innerHTML).indexOf('*');
        operand2 = parseInt((result.innerHTML).substring(index + 1), 2);
        subResult = equals * operand2;
    }
    else if (symbol == '/') {
        index = (result.innerHTML).indexOf('/');
        operand2 = parseInt((result.innerHTML).substring(index + 1), 2);
        subResult = Math.floor(equals / operand2);
    }
    result.innerHTML = subResult.toString(2);
    if (result.innerHTML == 'NaN')
        result.innerHTML = '0'; 
}
```
## Experience
Learning experience:
* [BinaryCalculator](https://github.com/duxa2089/TodoList)
* [TodoList](https://github.com/duxa2089/BinaryCalculator)
