---
layout: post
title: "Vid2Param: Online system identification from video for robotics applications"
date: 2019-07-15 10:40:04
categories: arXiv_RO
tags: arXiv_RO Prediction
author: Martin Asenov, Michael Burke, Daniel Angelov, Todor Davchev, Kartic Subr, Subramanian Ramamoorthy
mathjax: true
---

* content
{:toc}

##### Abstract
Robots performing tasks in dynamic environments would benefit greatly from understanding the underlying environment motion, in order to make future predictions and to synthesize effective control policies that use this inductive bias. Online system identification is therefore a fundamental requirement for robust autonomous agents. When the dynamics involves multiple modes (due to contacts or interactions between objects), and when system identification must proceed directly from a rich sensory stream such as video, then traditional methods for system identification may not be well suited. We propose an approach wherein fast parameter estimation with a model can be seamlessly combined with a recurrent variational autoencoder. Our Physics-based recurrent variational autoencoder model includes an additional loss that enforces conformity with the structure of a physically based dynamics model. This enables the resulting model to encode parameters such as position, velocity, restitution, air drag and other physical properties of the system. The model can be trained entirely in simulation, in an end-to-end manner with domain randomization, to perform online system identification, and probabilistic forward predictions of parameters of interest. We benchmark against existing system identification methods and demonstrate that Vid2Param outperforms the baselines in terms of speed and accuracy of identification, and also provides uncertainty quantification in the form of a distribution over future trajectories. Furthermore, we illustrate the utility of this in physical experiments wherein a PR2 robot with velocity constrained arm must intercept a bouncing ball, by estimating the physical parameters of this ball directly from the video trace after the ball is released.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.06422](http://arxiv.org/abs/1907.06422)

##### PDF
[http://arxiv.org/pdf/1907.06422](http://arxiv.org/pdf/1907.06422)

