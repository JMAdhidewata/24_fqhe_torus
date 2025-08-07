This repository contains the JupyterLab notebook used to calculate and plot the figures for "Excitation and tunneling spectra of a fractional quantum Hall system in the thin cylinder limit" (https://arxiv.org/abs/2507.21375).

The notebook contains four sections:
1. Calculation of the electron-electron interaction potentials on the torus (although we mostly used precomputed potentials),
2. Functions for calculating the energy and electron LDOS spectra based on the expressions we derived from perturbation theory in our paper,
3. Functions for preparing the Fock basis and the numerical Hamiltonian for exact diagonalization, and calculating the spectra using ED.
4. Plotting the results using matplotlib

You are free to reference or otherwise use parts of the code for your own work as long as credit is provided. Be aware that the code for building the Hamiltonian is written fully in Python and thus very slow. 
