# Abstraction vs Indirection

* Both hide things. Lot's of ppl define these differently. 

* Indirection hides location. 
  * ex : If you yell to someone in a building you might be able to hear them but not know exactly where they are.
  * Code Example: Classes don't have to know where their messages are going directly (might go to a super class); just need to send and receive messages.

* Abstraction hides complexity. 
  * When we write in Ruby, we are abstracting the fact that programming is really just a series of electrical pulses (ie 0's and 1's)
  * A method can also be thought of as an abstraction because once they are written we don't need to know the internals just the inputs and the outputs. 
