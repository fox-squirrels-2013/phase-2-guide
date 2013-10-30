## 4 Elements of Simple Design

```
def plus_1_to_number(number)  
  num=number  
  num=num
  return num  
end
```

* 1: Code should pass all tests. 
Now this code will pass the test `plus_1_to_number(5).should be 6` 

```
def plus_1_to_number(number)  
  num=number  
  num=num+1
  return num  
end


* 2: Make it DRY   
Here is dryer code: 
```
def plus_1_to_number(number)  
  num=number +1 
  return num  
end
```

* 3: Make sure you code clearly expresses intent (naming is key here). 
```
def add_1(number)  
  num=number +1  
  return num  
end
```

* 4: Minimize the number of classes methods and definitions (refactor)

```
def add(initial, incrementer)  
  initial + incrementer
end
```