# **Functions**
 ## function is a block of code designed to perform a particular task.

## **Function Syntax:**
### - function is defined with the function keyword, followed by a name, followed by parentheses ().

### - The parentheses may include parameter names separated by commas: (parameter1, parameter2, ...)

### - The code to be executed, by the function, is placed inside curly brackets: {}

~~~
function name(parameter1, parameter2) {
  // code to be executed
}
~~~

### ***You can use a function declaration or a function expression:***
## **function declaration :**
 ~~~
function SayHello(){

    document.write('Hello!');
}
SayHello();    //function call

 ~~~

 ## **function expression:**
~~~
function getArea(width,height){

    return width*height;
}
getArea(3,5);    //function call
~~~