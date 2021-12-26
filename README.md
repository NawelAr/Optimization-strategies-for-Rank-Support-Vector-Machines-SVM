# Optimization strategies for (Rank)-Support-Vector-Machines 

This work was carried out within the scope of the "Optimization for data science" course by Alexandre Gramfort and Robert Gower.
The project was carried out in partnership with Pierre-André Mikem.

## Aim:

- Derive the duals for SVMs for binary classification with and without intercept
- Implement an SVM using a blackbox convex toolbox (cvxopt in Python)
- Implement solvers for the "without intercept" case: Proximal gradient, Coordinate Descent, Newton, Quasi-Newton
- Use these solvers to tackle the SVM-rank ML problem
- Present a clear benchmark of the different strategies on small and medium scale datasets
- Test the code on real data!
