##Testing JavaScript in Your Web Apps
* [Code](https://github.com/gopher-snakes-2013/dummy-jasmine)
* [Video](http://talks.devbootcamp.com/setting-up-jasmine-breakout)

### Add Jasmine

* Add to your gemfile: `gem jasmine`
* In the console, type: `jasmine init`
* Add source files to `public/javascripts` files and they will be loaded when
  you run jasmine
* Add spec files to `spec/javascripts` named `file_name_spec.js` and they will
  be loaded when you run jasmine
* Add `public/javascript/vendor` folder for jQuery and other dependencies

### Add jasmine-jquery and jasmine-fixture
* Save these and any other testing libraries to the `spec/javascripts/helpers`
  directory.
* [jasmine-jquery](https://github.com/velesin/jasmine-jquery)
* Jasmine-Jquery makes it easy to test against the DOM using jQuery. It comes
  with dozens of matchers like 'toHaveClass' or 'toHandleWith' which allow you to
  express your desired behavior with very little work
* [jasmine-fixture](https://github.com/searls/jasmine-fixture)
* Jasmine-fixture makes it a snap to insert stuff into the DOM without doing a
  ton of work. Your JavaScript is often going to be coupled to the DOM; so you'll
  be doing a lot of tests which have to deal with your HTML structure.

### Maybe add jasmine Given
* Read the docs: [jasmine-given](https://github.com/searls/jasmine-given)
* Watch the video by Justin Searls on [javascript testing
  tactics](https://speakerdeck.com/searls/javascript-testing-tactics)

### Wire it all together
* Update the ```jasmine.yml``` file to link to your public files and spec files. 