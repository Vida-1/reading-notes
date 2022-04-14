#### 04/15/2022: Read 10 - JS Debugging

#### JS Chapter 10: “Error Handling & Debugging" (pp 449-486)
* Order of execution is the order in which Java processes statements.
* There are two execution contexts presented in this book one is global the other is function context.
* These contacts correlate with global scope and function level scope.
* When Java is processing statements it does so in a process that is analogous to putting them in a stackand then processing them from top to bottom.
* Hoisting refers to JavaScript ability to run functions that occur later in the order of the code in order to process function calls as required.
* The term lexical scope refers to scope within a function.
* Errors in your code will throw an exception causing interpreter to stop and look a series of statements to handle the error this is called exception handling code.
* Error objects help you find bugs are your code examples of error objects are error syntax error reference error type error range error urri error eval error. More details on error objects may be found on pages 460 - 462.
* Errors may contain properties such as name message file number and line number.
* Browsers contain JavaScript consoles in Chrome press F12 select tools JavaScript console or developer tools.
* In addition to console.log() there are other console functions useful in debugging such as console.info () console.warn(), and console.error(). See pages 472 and 473.
* Console.assert() allows dev to test if a condition is met and write to the console if the condition is false.
* You can select breakpoints using your web browser to stop your code from running in order to assist in debugging.
* With breakpoints you can step through the codeas a method for debugging.
* Breakpoints can be conditional.
* Learn more about the debugger keyword as well as handling exceptions with try catch and finally and throwing errors for not a number on pages 479 three 484.
* There's a list of common errors on page 485.
  
#### `Why this topic matters`
* If you never learn to debug your code you will likely never write any code that actually works.
    
#### `Analogy `
* Writing code without knowing how to debug would be akin to trying to bake something new without any frame of reference for your ingredients, a cookbook, or a sense of taste.

#### `Things I want to know more about`
* Javascript's "stacking" model.