---
layout: post
title: "A General Framework for Uncertainty Estimation in Deep Learning"
date: 2019-07-16 08:46:03
categories: arXiv_CV
tags: arXiv_CV Adversarial Inference Deep_Learning Prediction Quantitative
author: Mattia Seg&#xf9;, Antonio Loquercio, Davide Scaramuzza
mathjax: true
---

* content
{:toc}

##### Abstract
End-to-end learning has recently emerged as a promising technique to tackle the problem of autonomous driving. Existing works show that learning a navigation policy from raw sensor data may reduce the system's reliance on external sensing systems, (e.g. GPS), and/or outperform traditional methods based on state estimation and planning. However, existing end-to-end methods generally trade off performance for safety, hindering their diffusion to real-life applications. For example, when confronted with an input which is radically different from the training data, end-to-end autonomous driving systems are likely to fail, compromising the safety of the vehicle. To detect such failure cases, this work proposes a general framework for uncertainty estimation which enables a policy trained end-to-end to predict not only action commands, but also a confidence about its own predictions. In contrast to previous works, our framework can be applied to any existing neural network and task, without the need to change the network's architecture or loss, or to train the network. In order to do so, we generate confidence levels by forward propagation of input and model uncertainties using Bayesian inference. We test our framework on the task of steering angle regression for an autonomous car, and compare our approach to existing methods with both qualitative and quantitative results on a real dataset. Finally, we show an interesting by-product of our framework: robustness against adversarial attacks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.06890](http://arxiv.org/abs/1907.06890)

##### PDF
[http://arxiv.org/pdf/1907.06890](http://arxiv.org/pdf/1907.06890)

