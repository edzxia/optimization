# optimization
Various nonlinear optimization algorithms implemented in Python for parts of homework assignments in a graduaute Nonlinear Optimization class

optimization-1 contains the following algorithms for a simple quadratic objective function
  - Standard Gradient Descent
  - Exact Line Search
  - Lagged Line Search
  - Nesterov Acceleration for Smooth, Convex objective
  - A modified Nesterov that descends at least as much as standard Gradient Descent at each iteration
  - A modified Lagged Line Search that if the objective function increaes, will not iterate with that step length
  
optimization-2 contains some of the same algorithms from before and in addition (also for a simple quadratic objective function),
  - Nesterov Acceleration for Smooth, Strongly Convex objective
  - Heavy ball method
  
optimization-3 contains for an objective function that maximizes the inner product of the input and randomly generated Rademacher vectors on an L1 and L2 ball
  - Projected Subgradient Descent
  - Mirror Descent with negative entropy function

and for an objective function that maximizes a quadratic function with a matrix whose elements are drawn i.i.d. from Gaussian distribution on the probability simplex
  - Projected Subgradient Descent
  - Franke-Wolfe method
