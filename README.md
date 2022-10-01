# Transient-Diffusion-Time-Calculator
A simple project made in Matlab that allows to compute the time necessary to obtain the concentration of carbon at a given deep in a single carburization process. It relies in the aproximation by a lookup table to solve the error function that governs Fick´s second law. 

It contains two main files and a data file (.mat)

- Mlx livescript where the user can observe all the calculation results introducing the intended boundary conditions. At the end it displays the appropiate time needed.
- Slx Simulink file that process all the calculations needed. It doesn´t need to be opened by the user.

References used in the making of this project:

- Materials Science and Engineering: An Introduction. William D. Callister, David G. Rethwisch.
