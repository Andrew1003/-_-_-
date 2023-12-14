# RR Project: Nonlinear Equation Solver

A Python package for solving nonlinear equations in Data Science applications.

## Usage

To use the nonlinear equation solver, follow these steps:

```python
from rr_project_nonlinear.src.nonlinear_solver import NonlinearSolver, nonlinear_solver_decorator

# Define the equation and initial guess
equation = lambda x: x**2 - 4
initial_guess = 2

# Create the solver instance
solver = NonlinearSolver()

# Solve the equation
solution = solver.solve_equation(equation, initial_guess)

print(f"Solution: {solution}")
# -_-_-
