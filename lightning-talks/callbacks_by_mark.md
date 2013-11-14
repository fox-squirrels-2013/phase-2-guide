# Callbacks

* Consider the following code.

```
function x(other_func){
  
  other_func("Boom")
}

function y(arg){
  console.log(arg)
}

function z(arg){
  alert(z)
}
```
* The functions `x` and `y` are being passed into the 
x(y)  //=> logs the word "BOOM" to the console

x(z)  //=> alerts the word "BOOM" to the browser

```
