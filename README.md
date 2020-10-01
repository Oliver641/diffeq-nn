# diffeq-nn

This repository contains Jupyter notebooks exploring the modeling of solutions of differential equations by neural networks, a pet project of mine.  It is meant to demonstrate some of my coding/machine learning abilities to those interested, since my professional work cannot be shared.

It currently contains 2 folders:

  simple_equations: 
  My earlier explorations into the subject before doing a literature review.  Many of the ideas arose from discussion with Dorian Goldman, but the code and architectures found within are my work.  I highly recommend looking at [simple_equations/4_simple.ipynb](https://github.com/Oliver641/diffeq-nn/blob/master/simple_equations/4_simple.ipynb).  While it is a very simple equation,   I think clearly demonstrates how a net can derive differential equations from data and the architecture found within is  only one or two realizations away from pde-net.
  
  pde: 
  This contains a 'closed book' replication of the architecture found within [PDE-Net](https://arxiv.org/abs/1710.09668): Learning PDEs from Data, 
  a paper by Zichao Long, Yiping Lu, Xianzhong Ma, and Bin Dong.
  The notebooks found in this folder are me recreating their work from this paper without looking at their code as a learning exercise.  You can compare it to the authors' 
  code [here](https://github.com/ZichaoLong/PDE-Net).
  This involved creating a custom layer/RNNCell within Tensorflow 2, the DeltaT block.  Look at [pde/2_pde_net_replication.ipynb](https://github.com/Oliver641/diffeq-nn/blob/master/pde/2_pde_net_replication.ipynb) in order to see this.
