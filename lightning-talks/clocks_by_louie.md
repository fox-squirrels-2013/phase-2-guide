#Scheduled Jobs

* Use a clock method and a background worker.
* The clock fills the queue for the background worker.
* The background worker is on another server.

* Check out [Sidekiq](http://sidekiq.org/)  or [Heroku Scheduler](https://addons.heroku.com/scheduler) which use separate dynos and rake tasks. 

* Scaling - each rake task spins up a new dyno - need to be more efficient to not overload your dynos = expensive.
