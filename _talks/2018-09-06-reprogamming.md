---
title: "LabMeeting: Adversarial Reprogramming of Neural Networks"
collection: talks
type: "LabMeeting"
permalink: /talks/2018-09-06-reprogramming
venue: "SAILab"
date: 2018-09-06
location: "Siena, Italy"
---
Adversarial examples are defined as “inputs to machine learning models that an attacker has intentionally designed to cause the model to make a mistake”.
Indeed, in the computer vision scenario it has been shown that well-crafted perturbation to input images can induce classification errors, such as confusing a cat with a computer.
In general, adversarial attacks are designed to degrade the performances of models or to prompt the prediction of specific output classes.
In this recent work, the authors introduce a framework in which the goal of adversarial attacks is to reprogram the target model to perform a completely new task.
This is accomplished by optimizing for a single adversarial perturbation that can be added to all test-time inputs.
In such a way, the target model performs a task chosen by the adversary when processing these inputs—even if it was not trained on this task.

