---
title: "Inductive–Transductive Learning with Graph Neural Networks"
collection: publications
permalink: /publication/2018-08-30-inductive_transductive
excerpt: '8th IAPR TC3 Workshop, ANNPR 2018 - Inductive–Transductive Learning GNNs'
date: 2018-08-30
venue: '8th IAPR TC3 Workshop, ANNPR 2018'
paperurl: 'https://link.springer.com/chapter/10.1007%2F978-3-319-99978-4_16'
citation: 'Rossi, A., Tiezzi, M., Dimitri, G. M., Bianchini, M., Maggini, M., & Scarselli, F. (2018, September). &quot;Inductive–transductive learning with graph neural networks. &quot; IAPR Workshop on Artificial Neural Networks in Pattern Recognition (pp. 201-212). Springer, Cham. <i>8th IAPR TC3 Workshop, ANNPR 2018</i>'
---

Graphs are a natural choice to encode data in many real–world applications. In fact, a graph can describe a given pattern as a complex structure made up of parts (the nodes) and relationships between them (the edges). Despite their rich representational power, most of machine learning approaches cannot deal directly with inputs encoded by graphs. Indeed, Graph Neural Networks (GNNs) have been devised as an extension of recursive models, able to process general graphs, possibly undirected and cyclic. In particular, GNNs can be trained to approximate all the “practically useful” functions on the graph space, based on the classical inductive learning approach, realized within the supervised framework. However, the information encoded in the edges can actually be used in a more refined way, to switch from inductive to transductive learning. In this paper, we present an inductive–transductive learning scheme based on GNNs. The proposed approach is evaluated both on artificial and real–world datasets showing promising results. The recently released GNN software, based on the Tensorflow library, is made available for interested users.



Recommended citation: 
```
@inproceedings{rossi2018inductive,
  title={Inductive--transductive learning with graph neural networks},
  author={Rossi, Alberto and Tiezzi, Matteo and Dimitri, Giovanna Maria and Bianchini, Monica and Maggini, Marco and Scarselli, Franco},
  booktitle={IAPR Workshop on Artificial Neural Networks in Pattern Recognition},
  pages={201--212},
  year={2018},
  organization={Springer}
}
```