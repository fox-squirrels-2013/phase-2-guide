# Testing and TDD

Testing your code is a fantastic idea because it:

1. Forces you to think critically about what your code does
1. Helps you break big, unmanageable problems into small, manageable problems
1. Gives indicators for how clean your design is
1. Provides a reference for others to understand what your code does
1. Weaves a safety net for refactoring without worrying about breaking the
   code.

Below is a series of behaviors and objectives that demonstrate your ability to
test effectively.

## :+1:
1. I sometimes follow TDD's [Red Green
   Refactor](http://www.jamesshore.com/Blog/Red-Green-Refactor.html)
1. I test the [happy path](https://en.wikipedia.org/wiki/Happy_path)
1. My tests follow the [arrange act
   assert](http://agileinaflash.blogspot.com/2009/03/arrange-act-assert.html)
   pattern
1. I use rspec to test my classes and methods
1. I follow BetterSpec's guide on how to [describe
   methods](http://betterspecs.org/#describe)
1. My tests have a [single expectation](http://betterspecs.org/#single)
1. I am familiar with [test
   doubles](http://martinfowler.com/bliki/TestDouble.html) and can use stubs.
1. I'm familiar with the [Agile Testing
   Quadrants](http://www.exampler.com/old-blog/2003/08/21/#agile-testing-project-1)

## :+1: :+1:
1. I often follow TDD's [Red Green
   Refactor](http://www.jamesshore.com/Blog/Red-Green-Refactor.html)
1. I test several possible outcomes for a given method
1. I use pain I feel when testing as an indicator for how well designed code is.
1. I extract modules to share functionality between multiple spec files
1. I use [let](http://betterspecs.org/#let) for test setup
1. I use [subject](http://betterspecs.org/#subject) with
   [contexts](http://betterspecs.org/#contexts) to dry up my tests
1. I regularly commit after finishing a red-green-refactor cycle
1. I use rspec and capybara to test from the users perspective
1. I write user-facing tests and technology-facing tests
1. I regularly use stubs as stand ins for
   [collaborators](http://www.inf.ed.ac.uk/teaching/courses/inf1/op/Tutorials/2008/crc.html)

## :+1: :+1: :+1:
1. I always follow TDD's [Red Green
   Refactor](http://www.jamesshore.com/Blog/Red-Green-Refactor.html), except
   when spiking.
1. I commit every time I make a test pass and after completing a refactoring
1. I use [continuous
   integration](http://about.travis-ci.org/docs/user/languages/ruby/) to run all
   tests on every push
1. I'm aware of the differences between spies, stubs, fakes and mocks and use
   them each appropriately

