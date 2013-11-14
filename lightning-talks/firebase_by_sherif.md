# Firebase

* Lives in the cloud
* Has CUD (not CRUD - no Read)
  * WHAT??? How do you get stuff out?

* There are events: value, child_added, child_removed, child_updated, child_moved  that you can listen for and if they are triggered you use the event to C, R, D.

* CANNOT read all in Firebase.  

* The structure is hierarchical and key: value pairs.

* Can nest key:value pairs (JSON) `{ 1: {2:a}}`

* Create : `push(json)`
* Update : `set(json)`
* Delete : `remove(json)`


* What's the benefit? **SPEED**
