---
layout: post
title: "ChauffeurNet: Learning to Drive by Imitating the Best and Synthesizing the Worst"
date: 2018-12-07 16:04:00
categories: arXiv_CV
tags: arXiv_CV
author: Mayank Bansal, Alex Krizhevsky, Abhijit Ogale
mathjax: true
---

* content
{:toc}

##### Abstract
Our goal is to train a policy for autonomous driving via imitation learning that is robust enough to drive a real vehicle. We find that standard behavior cloning is insufficient for handling complex driving scenarios, even when we leverage a perception system for preprocessing the input and a controller for executing the output on the car: 30 million examples are still not enough. We propose exposing the learner to synthesized data in the form of perturbations to the expert's driving, which creates interesting situations such as collisions and/or going off the road. Rather than purely imitating all data, we augment the imitation loss with additional losses that penalize undesirable events and encourage progress -- the perturbations then provide an important signal for these losses and lead to robustness of the learned model. We show that the ChauffeurNet model can handle complex situations in simulation, and present ablation experiments that emphasize the importance of each of our proposed changes and show that the model is responding to the appropriate causal factors. Finally, we demonstrate the model driving a car in the real world.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.03079](http://arxiv.org/abs/1812.03079)

##### PDF
[http://arxiv.org/pdf/1812.03079](http://arxiv.org/pdf/1812.03079)

