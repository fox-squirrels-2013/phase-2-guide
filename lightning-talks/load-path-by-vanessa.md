## Environment Variables and $LOAD_PATH

* Environment Variables are provided by ruby and help store data.

* The $LOAD_PATH gives you an array of all files required for the particular file to run.

* In our skeletons we have seen the code: 
```
File.expand(__FILE__)
``` 
which gives the path of the current file. and 

```
$LOAD_PATH=File.unshift(File.expand(__FILE__))
```

