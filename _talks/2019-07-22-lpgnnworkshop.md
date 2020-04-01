---
title: "ACDL Satellite Workshop on Graph Neural Networks - Graph Neural Networks – A constraint-based formulation"
collection: talks
type: "Workshops"
permalink: /talks/2019-07-22-lpgnnworkshop
venue: "SAILab"
date: 2019-07-22
location: "Siena, Italy"
---

GNNs exploit a set of state variables, each assigned to a graph node, and a diffusion mechanism of the states among neighbor nodes, to implement an iterative procedure to compute the fixed point of the (learnable) state transition function. We propose a novel approach to the state computation and the learning algorithm for GNNs, based on a constraint optimization task solved in the Lagrangian framework. The state convergence procedure is implicitly expressed by the constraint satisfaction mechanism and does not require a separate iterative phase for each epoch of the learning procedure. In fact, the computational structure is based on the search for saddle points of the Lagrangian in the adjoint space composed of weights, neural outputs (node states), and Lagrange multipliers.