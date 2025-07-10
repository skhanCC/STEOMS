# (Stochastic) Truncated Equations Of Motion - (S)TEOMs
Mathematica-Python code for an approximate second-order cumulants approach to simulate - most generally - the measurement-conditioned dynamics of nonlinear, arbitrarily-multimode bosonic quantum systems under continuous heterodyne monitoring.
This code is able to compute both Truncated Equations of Motion that describe unconditional (or ensemble-averaged) dynamics, as well as Stochastic Truncated Equations of Motion (STEOMs) that described heterodyne-measurement-conditioned stochastic evolution.

This repository includes the following:
- Documentation '**STEOMS_Documentation.pdf**', describing how each term of a Lindblad master equation is implemented in the Mathematica code, and how the analytically-derived equations can be efficiently translated to Python code for numerical simulations.
- General Mathematica code for arbitrary master equations, in the Mathematica notebook '**TEOMSCalculator.nb**'.
- Example of how to translate Mathematica-calculated equations to Python code for numerical simulation  is included in the Jupyter notebook '**TEOMSExample.ipynb**'.
- Example Mathematica notebooks '**TEOMSCalculator-1QS-1QNP.nb**' and '**STEOMSCalculator-1QS-1QNP.nb**' to derive TEOMs and STEOMs respectively for a single-mode linear quantum system coupled to a single mode quantum nonlinear processor comprising a Kerr oscillator (see [1] for system details).
- Example Python code '**STEOMSExample-1QS-1QNP.ipynb**' to simulate TEOMs and STEOMs that are computed using the Mathematica notebooks referenced in the previous item, for a single-mode linear quantum system coupled to a single mode quantum nonlinear processor comprising a Kerr oscillator (see [1] for system details).

--

Version info:

-- Mathematica notebooks have been checked for compatibility with Wolfram Mathematica 14.0.

If you find this code useful, please consider citing: 

[1] https://arxiv.org/abs/2409.03748
