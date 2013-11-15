# Namespacing

* Allows you to group code so you don't have name collisions.

* Can be a big problem with 3rd party library inclusion.  If there is a naming conflict only the library loaded last will be used.

* Solution - Namespace in global object literal.


```
var mynamespace = mynamespace || {

function foo(){
  return "foo"  
}

function punch(){
  return "bear"
}


}

```

* Call `mynamespace.foo()`

* Using the `||` to avoid loading a namespace more than once (in case you choose a namespace that is in conflict with another)

* Use email or domain names to have unique namespace names. 