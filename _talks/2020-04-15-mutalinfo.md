---
title: "LabMeeting: On Mutual Information Maximization for Representation Learning"
collection: talks
type: "LabMeeting"
permalink: /talks/2020-04-15-mutualinfo
venue: "SAILab"
date: 2020-04-15
location: "Siena, Italy"
---
On Mutual Information Maximization for Representation Learning - An excursus into Deep InfoMax, its variants and their lacks

Many recent methods for unsupervised or self-supervised representation learning train feature extractors by maximizing an estimate of the mutual information (MI) between different views of the data. This comes with several immediate problems. For example, MI is notoriously hard to estimate, and using it as an objective for representation learning may lead to highly entangled representations due to its invariance under arbitrary invertible transformations. Nevertheless, these methods have been repeatedly shown to excel in practice. For instance, the DeepInfomax approach shows that structure matters, and that incorporating knowledge about locality in the input into the objective can significantly improve a representation’s suitability for downstream tasks. Moreover, they further control characteristics of the representation by matching to a prior distribution adversarially.
Some recent works argue, and provide empirical evidence, that the success of these methods cannot be attributed to the properties of MI alone, and that they strongly depend on the inductive bias in both the choice of feature extractor architectures and the parametrization of the employed MI estimators. Finally, these works establish a connection to deep metric learning and argue that this interpretation may be a plausible explanation for the success of the recently introduced methods.


<h5>References</h5>

- "Learning deep representations by mutual information estimation and
maximization",  R Devon Hjelm, Alex Fedorov, Samuel Lavoie-Marchildon, Karan Grewal, Phil Bachman, Adam Trischler, Yoshua Bengio (ICLR 2019)
- "On Mutual Information Maximization for Representation Learning",  Michael Tschannen, Josip Djolonga, Paul K. Rubenstein, Sylvain Gelly, Mario Lucic (ICLR 2020)


<h5>Resources</h5>
<a href="http://sailab.diism.unisi.it/apr-15-2020-labmeeting-on-mutual-information-maximization-for-representation-learning/">On Mutual Information Maximization presentation on SAILab </a>

<a href="https://mtiezzi.github.io/files/mutual_info.pdf">On Mutual Information Maximization slides</a>
