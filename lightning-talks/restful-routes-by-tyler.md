## RESTful Routes

### Request Verbs
Verbs can be mapped to CRUD actions. 


* `post` - used to create a record (Crud)
* `get` - used to show or read records (cRud)
* `put` - used for updating a record (crUd)
* `delete` - used to delete a record (delete of cruD)


### Request URL

The url should describe the resource being created. There are 7 restful routes which combine the verb and the url. 

* `get '/photos'` to read all photos
* `get '/photos/:id' to read a single photo
* `get '/photos/new' to show a new page with a form form creating a new photo.
*  `post '/photos'` to create a new photo
* `get '/photos/update' to show a new page with a form form creating a new photo.
* `put /photos/:id` to update a photo.
* `delete /photos/:id` to delete a photo.