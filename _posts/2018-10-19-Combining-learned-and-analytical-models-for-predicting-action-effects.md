---
layout: post
title: "Combining learned and analytical models for predicting action effects"
date: 2018-10-19 14:48:35
categories: arXiv_RO
tags: arXiv_RO Knowledge GAN CNN Prediction
author: Alina Kloss, Stefan Schaal, Jeannette Bohg
mathjax: true
---

* content
{:toc}

##### Abstract
One of the most basic skills a robot should possess is predicting the effect of physical interactions with objects in the environment. This enables optimal action selection to reach a certain goal state. Traditionally, dynamics are approximated by physics-based analytical models. These models rely on specific state representations that may be hard to obtain from raw sensory data, especially if no knowledge of the object shape is assumed. More recently, we have seen learning approaches that can predict the effect of complex physical interactions directly from sensory input. It is however an open question how far these models generalize beyond their training data. In this work, we investigate the advantages and limitations of neural network based learning approaches for predicting the effects of actions based on sensory input and show how analytical and learned models can be combined to leverage the best of both worlds. As physical interaction task, we use planar pushing, for which there exists a well-known analytical model and a large real-world dataset. We propose to use a convolutional neural network to convert raw depth images or organized point clouds into a suitable representation for the analytical model and compare this approach to using neural networks for both, perception and prediction. A systematic evaluation of the proposed approach on a very large real-world dataset shows two main advantages of the hybrid architecture. Compared to a pure neural network, it significantly (i) reduces required training data and (ii) improves generalization to novel physical interaction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1710.04102](http://arxiv.org/abs/1710.04102)

##### PDF
[http://arxiv.org/pdf/1710.04102](http://arxiv.org/pdf/1710.04102)

