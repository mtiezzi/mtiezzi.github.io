---
title: "Lagrangian Propagation Graph Neural Networks"
collection: publications
permalink: /publication/2020-02-07-dlgma_lpgnn
excerpt: 'AAAI20 - DLGMA Workshop paper - LPGNN'
date: 2020-02-07
venue: 'AAAI20 - DLGMA Workshop paper'
paperurl: 'https://dlg2019.bitbucket.io/aaai20/'
citation: 'Matteo Tiezzi, Giuseppe Marra, Stefano Melacci, Marco Maggini and Marco Gori (2020). &quot;Lagrangian Propagation Graph Neural Networks &quot; <i>AAAI20 - DLGMA Workshop</i>'
---

In the last years, the popularity of deep learning techniques has
renewed the interest in neural models able to process complex
patterns, that are naturally encoded as graphs. In particular,
different architectures have been proposed to extend the original Graph Neural Network (GNN) model. GNNs exploit a
set of state variables, each assigned to a graph node, and a
diffusion mechanism among neighbor nodes, to implement an
iterative state update procedure that computes the fixed point
of the (learnable) state transition function. In this paper, we
propose a novel approach to state computation and learning for
GNNs, based on a constraint optimisation task solved in the
Lagrangian framework. The state convergence procedure is
implicitly expressed by the constraint satisfaction mechanism
and does not require a separate iterative phase for each epoch
of the learning procedure. In fact, the computational structure
is based on the search for saddle points of the Lagrangian in
the adjoint space of weights, neural outputs (node states), and
Lagrange multipliers. The proposed approach is compared experimentally with other popular models for processing graphs.

[Download paper here](http://mtiezzi.github.io/files/DLGMA_2020_paper_28.pdf)

Recommended citation: 
Matteo Tiezzi, Giuseppe Marra, Stefano Melacci, Marco Maggini and Marco Gori (2020). "Lagrangian Propagation Graph Neural Networks" <i>AAAI20 - DLGMA Workshop</i>.