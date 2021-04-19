---
title: "Deep Constraint-based Propagation in Graph Neural Networks"
collection: publications
permalink: /publication/2021-04-15-lpgnn-TPAMI
excerpt: 'TPAMI - Deep LP-GNNs'
date: 2021-04-15
venue: 'TPAMI'
paperurl: 'https://papers.nips.cc/paper/2020/hash/fc2dc7d20994a777cfd5e6de734fe254-Abstract.html'
citation: 'Matteo Tiezzi, Giuseppe Marra, Stefano Melacci, Marco Maggini (2021). &quot;Deep Constraint-based Propagation in Graph Neural Networks &quot; <i>TPAMI</i>'
---

The popularity of deep learning techniques renewed the interest in neural architectures able to process complex structures that can be represented using graphs, inspired by Graph Neural Networks (GNNs). We focus our attention on the originally proposed GNN model of Scarselli et al. 2009, which encodes the state of the nodes of the graph by means of an iterative diffusion procedure that, during the learning stage, must be computed at every epoch, until the fixed point of a learnable state transition function is reached, propagating the information among the neighbouring nodes. We propose a novel approach to learning in GNNs, based on constrained optimization in the Lagrangian framework. Learning both the transition function and the node states is the outcome of a joint process, in which the state convergence procedure is implicitly expressed by a constraint satisfaction mechanism, avoiding iterative epoch-wise procedures and the network unfolding. Our computational structure searches for saddle points of the Lagrangian in the adjoint space composed of weights, nodes state variables and Lagrange multipliers. This process is further enhanced by multiple layers of constraints that accelerate the diffusion process. An experimental analysis shows that the proposed approach compares favourably with popular models on several benchmarks.

[Paper DOI](https://doi.org/10.1109/TPAMI.2021.3073504)

Recommended citation: 
```
@ARTICLE{9405452,
  author={M. {Tiezzi} and G. {Marra} and S. {Melacci} and M. {Maggini}},
  journal={IEEE Transactions on Pattern Analysis and Machine Intelligence}, 
  title={Deep Constraint-based Propagation in Graph Neural Networks}, 
  year={2021},
  volume={},
  number={},
  pages={1-1},
  doi={10.1109/TPAMI.2021.3073504}}
```