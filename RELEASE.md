# Release 0.1.4
 - Updated to work with tensorflow 0.9
 - Added a Logistic transform to enable contraining a parameter between two bounds
 - Added a Laplace distribution to use as a prior
 - Added a periodic kernel
 - Several improvements to the AutoFlow mechanism
 - added FITC approximation (see comparison notebook)
 - improved readability of code according to pep8
 - significantly improved the speed of the test suite
 - allowed passing of the 'tol' argument to scipy.minimize routine
 - added ability to add and multiply MeanFunction objects
 - Several new contributors (see README.md)

# Release 0.1.3
 - Removed the need for a fork of TensorFlow. Some of our bespoke ops are replaced by equivalent versions. 

# Release 0.1.2
 - Included the ability to compute the full covaraince matrix at predict time. See `GPModel.predict_f`
 - Included the ability to sample from the posterior function values. See `GPModel.predict_f_samples`
 - Unified code in conditionals.py: see deprecations in `gp_predict`, etc.
 - Added SGPR method (Sparse GP Regression)

# Release 0.1.1
 -  included the ability to use tensorflow's optimizers as well as the scipy ones

# Release 0.1.0
The initial release of GPflow. 
