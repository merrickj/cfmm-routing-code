# CFMM Optimal Routing
This repository contains the code needed to generate the figures used in the paper
[Optimal Routing for Constant Function Market Makers](https://stanford.edu/~guillean/papers/cfmm-routing.pdf).

## Requirements
The requirements for running these examples are:
- `NumPy`
- `Matplotlib`
- `Cvxpy` (see [here](https://www.cvxpy.org/install/index.html) for installation)

In order to generate the figures as done in the paper you will also need a working TeX distribution.

## How to run
All examples are self-contained and can be run directly, e.g.:
```bash
python arbitrage.py
```
The figures were generated by running
```bash
python two-asset.py
```
but note that this requires a working TeX distribution. (This can be avoided by commenting out any call to `latexify` in `two-asset.py` which requires `ps` as a backend for plotting.)