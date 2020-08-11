---
title: "A PyTorch implementation of The Graph Neural Network model"
collection: software
permalink: /software/2020-torchgnn
venue: "Italy, University of Siena, SAILab"
date: 2020-08-11
location: "Siena, Italy"
---

The Graph Neural Network (GNN) is a connectionist model particularly suited for problems whose domain can be represented by a set of patterns and relationships between them.

In those problems, a prediction about a given pattern can be carried out exploiting all the related information, which includes the pattern features, the pattern relationships and, in general, the whole graph that represents the domain. GNN peculiarity consists in its capability of computing the output prediction processing directly the input domain graph, without any preprocessing into a vectorial representation.

GNNs have been proved to be a universal approximator for a class of functions on graphs and have been applied to several tasks, including spam detection, object localization in images, molecule classification.

The framework
=============

The PyTorch porting was written by (me, :) in May 2020.

You can find a description of the model, installation/usage tutorials and some examples in the [Gnn site](https://mtiezzi.github.io/gnn_site).
I provide a [github repo](https://github.com/mtiezzi/torch_gnn) containing the implementation.