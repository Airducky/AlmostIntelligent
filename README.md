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
* `./Main points.csv` will train on 10000 entries of the generated XOR dataset.
  Should probably add testing and accuracy reporting at some point.
* Decided not to generalize element types to instances of Floating because
  Haskell's type system is insane. Could be done somewhat easily via
  GHC FlexibleContexts.
