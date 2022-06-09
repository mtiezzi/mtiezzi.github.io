---
title: "Stochastic Coherence Over Attention Trajectory For Continuous Learning In Video Streams"
collection: publications
permalink: /publication/2022-06-09-stochastic
excerpt: 'IJCAI2022'
date: 2022-06-09
venue: 'IJCAI2022'
paperurl: 'https://arxiv.org/abs/2204.12193'
citation: 'Matteo Tiezzi, Simone Marullo, Lapo Faggi, Enrico Meloni, Alessandro Betti, Stefano Melacci (2022). &quot;Stochastic Coherence Over Attention Trajectory For Continuous Learning In Video Streams &quot; <i>IJCAI</i>'
---

Devising intelligent agents able to live in an environment and learn by observing the surroundings is a longstanding goal of Artificial Intelligence. From a bare Machine Learning perspective, challenges arise when the agent is prevented from leveraging large fully-annotated dataset, but rather the interactions with supervisory signals are sparsely distributed over space and time. This paper proposes a novel neural-network-based approach to progressively and autonomously develop pixel-wise representations in a video stream. The proposed method is based on a human-like attention mechanism that allows the agent to learn by observing what is moving in the attended locations. Spatio-temporal stochastic coherence along the attention trajectory, paired with a contrastive term, leads to an unsupervised learning criterion that naturally copes with the considered setting. Differently from most existing works, the learned representations are used in open-set class-incremental classification of each frame pixel, relying on few supervisions. Our experiments leverage 3D virtual environments and they show that the proposed agents can learn to distinguish objects just by observing the video stream. Inheriting features from state-of-the art models is not as powerful as one might expect.

[Paper Arxiv](https://arxiv.org/abs/2204.12193)

Recommended citation: 
```
@article{tiezzi2022stochastic,
  title={Stochastic Coherence Over Attention Trajectory For Continuous Learning In Video Streams},
  author={Tiezzi, Matteo and Marullo, Simone and Faggi, Lapo and Meloni, Enrico and Betti, Alessandro and Melacci, Stefano},
  journal={arXiv preprint arXiv:2204.12193},
  year={2022}
}
```