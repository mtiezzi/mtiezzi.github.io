---
title: "Evaluating Continual Learning Algorithms by Generating 3D Virtual Environments"
collection: publications
permalink: /publication/2021-09-16-evaluating
excerpt: 'CSSL@IJCAI2021'
date: 2021-09-16
venue: 'CSSL@IJCAI2021'
paperurl: 'https://doi.org/10.1109/ICMLA52953.2021.00009'
citation: 'Enrico Meloni, Alessandro Betti, Lapo Faggi, Simone Marullo, Matteo Tiezzi, Stefano Melacci (2021). &quot;Evaluating Continual Learning Algorithms by Generating 3D Virtual Environments &quot; <i> CSSL@IJCAI2021 </i>'
---
Continual learning refers to the ability of humans and animals to incrementally learn over time in a given environment. Trying to simulate this learning process in machines is a challenging task, also due to the inherent difficulty in creating conditions for designing continuously evolving dynamics that are typical of the real-world. Many existing research works usually involve training and testing of virtual agents on datasets of static images or short videos, considering sequences of distinct learning tasks. However, in order to devise continual learning algorithms that operate in more realistic conditions, it is fundamental to gain access to rich, fully customizable and controlled experimental playgrounds. Focussing on the specific case of vision, we thus propose to leverage recent advances in 3D virtual environments in order to approach the automatic generation of potentially life-long dynamic scenes with photo-realistic appearance. Scenes are composed of objects that move along variable routes with different and fully customizable timings, and randomness can also be included in their evolution. A novel element of this paper is that scenes are described in a parametric way, thus allowing the user to fully control the visual complexity of the input stream the agent perceives. These general principles are concretely implemented exploiting a recently published 3D virtual environment. The user can generate scenes without the need of having strong skills in computer graphics, since all the generation facilities are exposed through a simple high-level Python interface. We publicly share the proposed generator.

[Paper DOI](https://sites.google.com/view/sscl-workshop-ijcai-2021/)

Recommended citation: 
```
@article{meloni2021evaluating,
  title={Evaluating Continual Learning Algorithms by Generating 3D Virtual Environments},
  author={Meloni, Enrico and Betti, Alessandro and Faggi, Lapo and Marullo, Simone and Tiezzi, Matteo and Melacci, Stefano},
  journal={arXiv preprint arXiv:2109.07855},
  year={2021}
}
```