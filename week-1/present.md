## Week 1 Team Presentations:


### Team 1: BLD (Daniel, Benny, Dom)

* Code we're proud of: 
  * NAVI constant array on routes page is used to populate the navigation bar on the index page. (**NOTE: Look at partials for this).
  * Single Table Inheritance. A discussion and a comment are stored in the same table. Each comment knows it's parent through the discussion id. 

* Code we struggled with:
  * Naming is clunky. Have 'smurf-naming' (ex: A Discussion class has a discussion_text attribute)

* Speaking suggestions:
  * 

### Team 2: Gary (Logan, Miya, Garreth, Tyler )

* Code we're proud of:
  * search: started by searching just for first name. Might be able to adjust for last name too. 
  * helpers:
  * group dynamic  
* Code we struggled with:
  * helpers: Originally put all of our code into a helper method. Now we know only logic that is needed in the view and the controller should be in the view.
  * merge hell: tried to do it all with one pull request - it failed!  
* Speaking suggestions:
  * Nice job giving an overview and having each member speak.

### Team 3: Shimango (Mo, Lindsey, Marion, )

* Code we're proud of:
  * Search by full name
  * BCrypt - (**NOTE: Move require statement to environment.rb**)
  * Friendships table is a many to many join table of two members. 

* Code we struggled with
  * Made a LOT of model calls from the view - should have been in the controller. Next time need to use an instance variable. 
* Speaking suggestions
  * Be sure to introduce your team and all group members to start. 

### Team 4: Merry Pranksters( Thomas, Louie, Nicole, Vanessa)

* Code we're proud of
  * Deploying to heroku - just need to change the arguments to `ActiveRecord::Base.establish_connection()`
* Code we struggled with
  * Pushed to master while other team working on views - merge hell. 
  * **NOTE: Split tasks vertically instead of horizontally to help avoid merge conflicts.**
* Speaking Suggestions:
  * Nice job explaining trello with team dynamics. 

### Team 5: Pinball Wizards (Mark, Ben, Brantley)
* Code we're proud of
  * Friend requests: added action to `post '/friend_request'` to choose send, accept, reject **NOTE: Use separate routes for each action**
  * Using local variables to allow access to session and login information in the view. `{:locals}` 
* Code we struggled with:
  * Using bcrypt - complexity of putting too much logic on one line of code. Also, switch the logic to test for "if good" instead of "if bad" for cleaner code. 

* Speaking suggestions:
  * Introduce your team members. 

### Team 6: Holo....? (Sherif, Marc, Mike, Tyler)
* Code we're proud of
  * CSS - use the psuedo property for edit `:hover ` and use absolute positioning to put an element on top of another. 
  * Git- lots of branches and commits.
* Code we struggled with
 *  Search : Our original code allows us to do a SQL injection attack () which we now know!
* Speaking suggestions:
  * ? not sure what you were doing with the brainstorming graphic - be sure inside jokes are clarified or skipped in presentations.  
  * Nice job explaining team dynamic. 
