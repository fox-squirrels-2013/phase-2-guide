# Closures

## Link it to Ruby

* Let's remember procs from ruby
```ruby
## Define a proc
our_first_proc=Proc.new{|x|x+1}

## Call a proc
 our_first_proc(3)

```

* Here's another example
```ruby
def add_num
 b=4
 return Proc.new{|x| x+b}
end

new_proc= add_num()
new_proc(3) # returns 7
```

This works.  You can get access to the variable `b` even though you call the proc when you are outside the scope.  **COOL**

* A proc remembers the scope it was defined in (and has access to the variables there) even if it is called in a different scope.


## In JavaScript
* Closures are the same as procs.
* A closure can be passed around as an argument
* A closure remembers it's original state.
