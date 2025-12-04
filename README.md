# Project_approx_for_pde
This code is not intended for "production". It was written specifically for my machine during my thesis project. 
If you intened to try it out for yourself you likely need to change stuff related to I/O, i.e location of saved files etc.

All the programs solve various instances of the Darcy problem.
Avalible models:
  - DeepONet trained on a threshold field
  - PINN model for a PDE; -D.(aDu) = f
  - PCA-Net Implementation for both a lognormal and a threshold field

To run the models you need to first generate a dataset. This can be done using the files in the DataGen folder.
