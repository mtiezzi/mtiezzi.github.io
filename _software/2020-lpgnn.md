---
title: "Lagrangian Propagation Graph Neural Network"
collection: software
permalink: /software/2020-lpgnn
venue: "Italy, University of Siena, SAILab"
date: 2020-09-19
location: "Siena, Italy"
---

In many real world applications, data are characterized by a complex structure, that can be naturally encoded as a graph. In the last years, the popularity of deep learning techniques has renewed the interest in neural models able to process complex patterns. In particular, inspired by the Graph Neural Network (GNN) model, different architectures have been proposed to extend the original GNN scheme. GNNs exploit a set of state variables, each assigned to a graph node, and a diffusion mechanism of the states among neighbor nodes, to implement an iterative procedure to compute the fixed point of the (learnable) state transition function. In this paper, we propose a novel approach to the state computation and the learning algorithm for GNNs, based on a constraint optimisation task solved in the Lagrangian framework. The state convergence procedure is implicitly expressed by the constraint satisfaction mechanism and does not require a separate iterative phase for each epoch of the learning procedure. In fact, the computational structure is based on the search for saddle points of the Lagrangian in the adjoint space composed of weights, neural outputs (node states), and Lagrange multipliers. The proposed approach is compared experimentally with other popular models for processing graphs.

Papers
======
- A Lagrangian Approach to Information Propagation in Graph Neural Networks
    - [ECAI2020](http://ebooks.iospress.nl/publication/55057)
    - DOI 10.3233/FAIA200262
    
- Deep Lagrangian Constraint-based Propagation in Graph Neural Networks
    - [Arxiv](https://arxiv.org/abs/2005.02392)
    
The framework
=============

The PyTorch code was written by Matteo Tiezzi (me, :) in August 2020.

I provide a [github repo](https://github.com/mtiezzi/lpgnn) containing the implementation.