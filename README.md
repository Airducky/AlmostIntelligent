AlmostIntelligent
=================

A repository full of AI/ML/DL and other delights.
You'll find implementations of various models and algorithms here as I learn more and try
my hand at coding them. As a bonus, I'll be practicing my functional programming,
but we'll see how long that lasts.

Listing of files:
* FFNN.hs First implementation of backpropagation. Depends on hmatrix,
  mwc-random, statistics.
* XorGen.hs Generates 3D XOR datasets for sanity testing. Depends on
  mwc-random, cassava.

### To Do's
__ffnn.hs__
* Made layers more configurable. Should winit be more flexible?
  winit could be made into an Either type for fixed vs random initialization.
* Decided not to generalize element types to instances of Floating because
  Haskell's type system is insane. Could be done somewhat easily via
  GHC FlexibleContexts.
