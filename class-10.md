# sumarization

### Code Debugging
Searching for (and fixing) errors in programming code is called code debugging.With a debugger, you can also set breakpoints (places where code execution can be stopped), and examine variables while the code is executing.

* The `console.log()` Method
* The debugger Keyword
The debugger keyword stops the execution of JavaScript, and calls (if available) the debugging function.This has the same function as setting a breakpoint in the debugger.If no debugging is available, the debugger statement has no effect.With the debugger turned on, this code will stop executing before it executes the third line.

###JavaScript Errors - Throw and Try to Catch
* The try statement lets you test a block of code for errors.

* The catch statement lets you handle the error.

* The throw statement lets you create custom errors.

* The finally statement lets you execute code, after try and catch, regardless of the result.
### JavaScript Throws Errors
When an error occurs, JavaScript will normally stop and generate an error message.the technical term for this is: JavaScript will throw an exception (throw an error).JavaScript will actually create an Error object with two properties: name and message.

#### The throw Statement
The throw statement allows you to create a custom error.Technically you can throw an exception (throw an error).The exception can be a JavaScript String, a Number, a Boolean or an Object The finally statement lets you execute code, after try and catch, regardless of the result:
**If you use throw together with try and catch, you can control program flow and generate custom error messages.**<br>
*Example*...<br>
` try {`<br>
    `if(x == "") throw "empty";`<br>
    `if(isNaN(x)) throw "not a number";`<br>
   ` x = Number(x);`<br>
    `if(x < 5) throw "too low";`<br>
    `if(x > 10) throw "too high";` <br>
  `}`<br>
  `catch(err) {`<br>
   ` message.innerHTML = "Input is " + err;`<br>
 ` }`<br>
`}`<br>



