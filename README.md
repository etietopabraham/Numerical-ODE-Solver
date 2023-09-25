# Numerical-ODE-Solver

This solution provides a comparison of various numerical methods to solve the differential equation y' = (y + x)^2 over the interval [0, 0.5].

The exact solution to this ODE is y(x) = tan(x) - x

**Methods Explored:**

- Euler Method
- Euler-Cauchy Method (also known as the Modified Euler or Heun's Method)
- Implicit Euler-Cauchy Method
- Runge-Kutta 4th Order Method (RK4)
- Adams-Bashforth 2-step Method

**Results**

The results showcase the performance of each numerical method in approximating the solution. The RK4 and Adams-Bashforth methods, being more sophisticated, tend to provide closer approximations to the true solution, while the basic Euler method has some deviations, especially as x increases.
