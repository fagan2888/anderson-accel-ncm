`anderson-accel-ncm` - MATLAB Codes for Anderson acceleration of the
alternating projections method for the nearest correlation matrix.
==========

About
-----

`anderson-accel-ncm` contains MATLAB functions for repairing
invalid (indefinite) covariance and correlation matrices, based on the
paper

N. J. Higham and N. Strabić, "[Anderson Acceleration of the Alternating
Projections Method for Computing the Nearest Correlation
Matrix](http://eprints.ma.man.ac.uk/2310/)", MIMS EPrint 2014.39,
Manchester Institute for Mathematical Sciences, The University of
Manchester, UK, August 2015.

The main functions are

* `nearcorr_new`: the alternating projections method for computing the
  nearest correlation matrix.  This is a version of the function at
  https://nickhigham.wordpress.com/2013/02/13/the-nearest-correlation-matrix/
  modified to include rthe options of fixing elements and imposing a lower
  bound on the smallest eigenvalue.

* `nearcorr_aa`: the alternating projections method for computing the
   nearest correlation matrix with Anderson acceleration.

Other M-files:

* `test_anderson`: a test function.  It runs the functions above on two test
   problems and reports the number of iterations.  It can be run by typing
   `test_anderson` with no arguments.

Requirements
-------------

The codes have been developed under MATLAB 2015a
and have been tested with MATLAB 2015b pre-release.

License
-------

See `license.txt` for licensing information.
