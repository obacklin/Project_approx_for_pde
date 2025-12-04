# Project_approx_for_pde
This code is not intended for production use. It was written specifically for my machine during my thesis project.
If you intend to try it out yourself, you will likely need to change things related to I/O, i.e., the locations of saved files, etc.

All the programs solve various instances of the Darcy problem −∇⋅(a∇u)=f.
Available models:
– DeepONet trained on a threshold field
– PINN model
– PCA-Net implementation for both a lognormal and a threshold field

To run the models, you first need to generate a dataset. This can be done using the files in the DataGen folder.
