# Active Record Finders

* Rails Guides are currently defaulting to 4.0 version (we are using 3.x)

* The code `find_by :email => "stuff@stuff.com"` doesn't work outside of 4.0 (even though it is in the guide) but `find_by_email("stuff@stuff.com")` does.

* How the heck does `find_by_email` and `find_by_anyfield` work anyway?
  * If method not found in the object or its super classes / included modules, then the `method_missing` method is called. 
  * Active Record overrides the `method_missing` method to have it create a method `find_by_whatever`