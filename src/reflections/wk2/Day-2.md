Tuesday 03/23/2021
Afternoon Link: https://github.com/Toppedyk/js-tests-loops-and-arrays

What are the three ways to syntactically write a function? What are the differences in how the function acts (if any)?
function name(parameters) {
    // statements
}

let name = function(parameters) {
    // statements
}

let name = (parameters) => {
    // statements
}

the syntax is the main difference between these and they will act the same. named functions(middle example) are not hoisted. arrow functions(last example) do not create a this variable.  

What is the difference between Parameters and Arguments?
parameters are inside the parenthasees when the function is declared. Arguments are passed in when the function is called. 

What are higher order functions? Can you provide an example?
a higher order function is when it takes another function as a parameter or returns a function. 
array.map & array.filter are both examples. 