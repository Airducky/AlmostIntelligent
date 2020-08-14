AlmostIntelligent
=================

A repository full of AI/ML/DL and other delights.
You'll find implementations of various models and algorithms here as I learn more and try
my hand at coding them. As a bonus, I'll be practicing my functional programming,
but we'll see how long that lasts.

Listing of files:
* ffnn.hs First implementation of backpropagation. Depends on hmatrix.

### To Do's
__ffnn.hs__
* Make activation functions configurable.
* Change checkLayers to take the description of the network before
  weight initialization.
* Decided not to generalize element types to instances of Floating because
  Haskell's type system is insane. Could be done somewhat easily via
  GHC FlexibleContexts.
  