# (Stochastic) Truncated Equations Of Motion - (S)TEOMs
Mathematica-Python code for an approximate second-order cumulants approach to simulate - most generally - the measurement-condition dynamics of nonlinear, arbitrarily-multimode bosonic quantum systems under continuous heterodyne monitoring.
This code is able to compute both Truncated Equations of Motion that describe unconditional (or ensemble-averaged) dynamics, as well as measurement-condition stochastic evolution.

See Documentation can be found in the overleaf document (until finalized):
https://www.overleaf.com/read/qkkjfwxwcngd

This repository includes the following:
- Documentation '.pdf', describing how each term of a Lindblad master equation is implemented in the Mathematica code, and how the analytically-derived equations can be efficiently translated to Python code for numerical simulations.
- General Mathematica code for arbitrary master equations, in the Mathematica notebook 'TEOMSCalculatorExample.nb'.
- Example of how to translated Mathematica-calculated equations to Python code for numerical simulation  is included in the Jupyter notebook 'TEOMSExample.ipynb'.
- Example Mathematica notebook to compute (S)TEOMs for single-mode quantum system coupled to a single mode quantum nonlinear processor comprising a Kerr oscillator (see [1] for system details).
- Example Python code to simulate (S)TEOMs computed using Mathematica for single-mode quantum system coupled to a single mode quantum nonlinear processor comprising a Kerr oscillator (see [1] for system details).

--

If you find this code useful, please consider citing: 
[1] https://arxiv.org/abs/2409.03748. 
