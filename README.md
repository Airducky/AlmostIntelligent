AlmostIntelligent
=================

A repository full of AI/ML/DL and other delights.
You'll find implementations of various models and algorithms here as I learn more and try
my hand at coding them. As a bonus, I'll be practicing my functional programming,
but we'll see how long that lasts.

Listing of files:
* FFNN.hs Fully-connected feed forward neural networks. Depends on hmatrix,
  mwc-random, statistics.
* XorGen.hs Generates 3D XOR datasets for sanity testing. Depends on
  mwc-random, cassava.
* LineGen.hs Generates a binary classification dataset based on a region defined
  by two lines. Depends on mwc-random, cassava.

The *Run.hs files compiled with 
`ghc -package vector -package primitive -package mtl -package split LineRun.hs`.

### To Do's
__ffnn.hs__
* Regularization
* Add `TrainingSpec` to make loss functions, regularization, and
  hyperparameters configurable and to ease passing values around.
* Decided not to generalize element types to instances of Floating because
  Haskell's type system is insane. Could be done somewhat easily via
  GHC FlexibleContexts.
