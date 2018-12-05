---
layout: post
title: "Learning to Predict Ego-Vehicle Poses for Sampling-Based Nonholonomic Motion Planning"
date: 2018-12-03 23:08:31
categories: arXiv_AI
tags: arXiv_AI CNN
author: Holger Banzhaf, Paul Sanzenbacher, Ulrich Baumann, J. Marius Z&#xf6;llner
mathjax: true
---

* content
{:toc}

##### Abstract
Sampling-based motion planning is an effective tool to compute safe trajectories for automated vehicles in complex environments. However, a fast convergence to the optimal solution can only be ensured with the use of problem-specific sampling distributions. Due to the large variety of driving situations within the context of automated driving, it is very challenging to manually design such distributions. This paper introduces therefore a data-driven approach utilizing a deep convolutional neural network (CNN): Given the current driving situation, future ego-vehicle poses can be directly generated from the output of the CNN allowing to guide the motion planner efficiently towards the optimal solution. A benchmark highlights that the CNN predicts future vehicle poses with a higher accuracy compared to uniform sampling and a state-of-the-art A*-based approach. Combining this CNN-guided sampling with the motion planner Bidirectional RRT* reduces the computation time by up to an order of magnitude and yields a faster convergence to a lower cost as well as a success rate of 100 % in the tested scenarios.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01127](http://arxiv.org/abs/1812.01127)

##### PDF
[http://arxiv.org/pdf/1812.01127](http://arxiv.org/pdf/1812.01127)

