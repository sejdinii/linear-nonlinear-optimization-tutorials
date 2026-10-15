# Optimisation Tutorials

Step-by-step, interactive walkthroughs of integer and nonlinear optimisation methods, worked the way you would on paper. I built them while studying optimisation, to make the methods easier to follow than textbook notation.

**Live site:** https://sejdinii.github.io/linear-nonlinear-optimization-tutorials/

## Tutorials

| Topic | Tutorial | What it covers |
|---|---|---|
| Integer and binary LP | Branch & Bound: Binary Knapsack | A full 15-node tree solved step by step: LP relaxation, branching, pruning, incumbent tracking (best-bound strategy) |
| Integer and binary LP | Gomory Cuts | Cutting planes from the simplex tableau: fractional parts, surplus variables, dual simplex re-solve |
| Integer and binary LP | Cover Constraints | Minimal covers, cover inequalities and how to strengthen them |
| Nonlinear programming | Derivative = 0 (Harris formula) | Unconstrained minima and maxima, the Harris inventory formula, local vs global |
| Nonlinear programming | Penalty Method | Equality constraints with a penalty term M·(constraint)², converging as M grows |
| Nonlinear programming | Barrier Method | Inequality constraints with a logarithmic barrier, compared with the penalty method |

Coming soon: Branch & Bound with integer variables, KKT conditions, the simplex method, two-phase simplex, sensitivity analysis, and duality and the dual simplex.

## Run locally

Plain HTML, CSS and JavaScript with no build step. Open `index.html` in a browser.
