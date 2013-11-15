# Naming Gems 

* Look to see if the name is available (on GitHub and RubyGems)
* You need underscores between each word.
* Replace / with -
* Use an underscore to indicate that you are adding functionality to an existing gem.  EX: if you extend `existing_gem` then you might get `existing_gem_cooler`

* Use semantic versioning to indicate what the version change is doing (major change, minor change, patch). Can also set "alpha", "beta", etc. 

* Set runtime dependencies for :production and :development

* Don't require rubygems in your gemfile. 

