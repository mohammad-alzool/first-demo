# functions
<p>&nbsp;</p>

![functions](img/functions.jpg)

## WHAT IS A FUNCTION ?

- Functions let you group a series of statements together to perform a
specific task. If different parts of a script repeat the same task, you can
reuse the function (rather than repeating the same set of st atements) 
&nbsp OR you can say

- A function in JavaScript is similar to a procedure a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output

why to use function in javascript ?

JavaScript provides functions similar to most of the scripting and programming languages. In JavaScript, a function allows you to define a block of code, give it a name and then execute it as many times as you want. A JavaScript function can be defined using function keyword

1. You can reuse code: Define the code once, and use it many times.
2. You can use the same code many times with different arguments, to produce different results.


Example
<p>&nbsp;</p>

Convert Fahrenheit to Celsius:
function toCelsius(fahrenheit)   {
  return (5/9) * (fahrenheit-32);
}
document.getElementById("demo").innerHTML = toCelsius(77);