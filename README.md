# Approximation Theory For PDE

This repository contains implementations of three frameworks for solving PDEs using neural networks; Physics Informed Neural Network(PINN), a Deep Operator Network(DeepONet), and an implementation of the so-called PCA-Net.
All implementations were made from scratch and are based on 4 papers.

https://arxiv.org/abs/1910.03193 (DeepONets)

https://arxiv.org/abs/2005.03180 (PCA-Net)

https://arxiv.org/abs/1711.10561 (PINNs) 

https://arxiv.org/abs/2407.17611v1 (Adaptive training algorithms for PINNs)

The code is not intended for production use. It was written specifically for my machine during my thesis project.
If you intend to try it out yourself, you will likely need to change things related to I/O, i.e., the locations of saved files, etc.

All the programs solve various instances of the Darcy problem −∇⋅(a∇u)=f.

Available models:
  - DeepONet trained on a threshold field
  - PINN model
  - PCA-Net implementation for both a lognormal and a threshold field

To run the models, you first need to generate a dataset. This can be done using the files in the DataGen folder.
