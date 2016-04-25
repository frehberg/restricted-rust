# restricted-rust

Declaring a restricted sub-set of rust language permitting termination analysis. During compilation time the restrictions can be verified and enforced for implementations of functions that are going to be executed in time-critical environment. 

Restrictions:
* covering function scope only
* no global variables
* just local immutable variables
* no while-loop
* for-loop with finite set of iterations only (with upper bound?)
* no dynamic memory allocation
* no invocation of sub routines.
