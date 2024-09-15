# Non-Convex-Penalty-Optimization
Explored the ‘Oracle Property’ of the SCAD(Smoothly Clipped Absolute Deviation) and MCP(Minimax Concave Penalty)
applied to Logistic Regression, and tested out various optimization algorithms for the loss function, such as Coordinate Descent,
Proximal Gradient Descent, and Stochastic Descent. The best combination of non-convex penalty and optimization algorithm was
picked, that is, the one that performed as good as the LARS algorithm would perform on a Logistic Regression loss function with
a convex penalty.
