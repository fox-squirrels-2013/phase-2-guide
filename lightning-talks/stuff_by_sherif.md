##

* Remember in Ruby when we wanted to add a method to `String`? ie
```
class String 
 ....
end

String.new_method 

````

* In JS we did 
`Math.floor(Math.log(Math.Random))`  and then refactored this code by opening the `Number` function and modifying it's prototype.

```
Number.prototype.logorithmic_rand = function(mult){
  var multiple = mult || 100
  return multiple

}

```