# What is Rack 

* "I can't actually write - because I'm a puppet" - from the puppet. 

* Things I know about Rack : 
  * A web server interface. 
  * Middleware
  * Baked into Sinatra and Rails
  * Responds to the `call` method
  * Responsible for receiving inputs from a web server (requests). Is the layer between your app and html.
  * Responds to a simple hash which is the request. 
    * with code, header, body

* Packages the request from the http protocol (which is really just a string) into objects that Ruby can use. 

