#Routes and Parameters

* In the route 
``` 
get /hello/:name do

end
```
the `:name` params can be accessed by `params[:name]`

* Block parameters
```
get /hello/:name do |n|

end
```
You can access `n` in your code without using the `params` hash.

* Splat (*)
```
get '/hello/*' do

end
``` 
accessible in `params[:splat]` 

* 
``` 
get '/download/*.*/' do |file,ext|
[file, ext]
end
``` 
returns file and extension. 
