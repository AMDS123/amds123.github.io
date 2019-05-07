---
layout: post
title: "Muscle Excitation Estimation in Biomechanical Simulation Using NAF Reinforcement Learning"
date: 2019-05-03 21:12:12
categories: arXiv_RO
tags: arXiv_RO Tracking Reinforcement_Learning
author: Amir H. Abdi, Pramit Saha, Praneeth Srungarapu, Sidney Fels
mathjax: true
---

* content
{:toc}

##### Abstract
Motor control is a set of time-varying muscle excitations which generate desired motions for a biomechanical system. Muscle excitations cannot be directly measured from live subjects. An alternative approach is to estimate muscle activations using inverse motion-driven simulation. In this article, we propose a deep reinforcement learning method to estimate the muscle excitations in simulated biomechanical systems. Here, we introduce a custom-made reward function which incentivizes faster point-to-point tracking of target motion. Moreover, we deploy two new techniques, namely, episode-based hard update and dual buffer experience replay, to avoid feedback training loops. The proposed method is tested in four simulated 2D and 3D environments with 6 to 24 axial muscles. The results show that the models were able to learn muscle excitations for given motions after nearly 100,000 simulated steps. Moreover, the root mean square error in point-to-point reaching of the target across experiments was less than 1% of the length of the domain of motion. Our reinforcement learning method is far from the conventional dynamic approaches as the muscle control is derived functionally by a set of distributed neurons. This can open paths for neural activity interpretation of this phenomenon.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.06121](http://arxiv.org/abs/1809.06121)

##### PDF
[http://arxiv.org/pdf/1809.06121](http://arxiv.org/pdf/1809.06121)

