# Numerical Interpolation

Numerical investigation of polynomial and radial basis function interpolation, developed as a project in TMA4215 Numerical Mathematics at NTNU.

The project studies Lagrange interpolation on equidistant and Chebyshev nodes, piecewise-polynomial interpolation, Gaussian radial basis functions, interpolation error and conditioning. It also explores gradient-based optimization of RBF nodes and shape parameters.

The main report, including mathematical analysis, numerical experiments and figures, is available in [`notebooks/project_1.ipynb`](notebooks/project_1.ipynb). Reusable implementations are organized under `src/`.

## Run

```bash
uv sync --extra dev
uv run jupyter lab notebooks/project_1.ipynb
```
