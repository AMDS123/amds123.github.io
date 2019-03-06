---
layout: post
title: "Deep Active Localization"
date: 2019-03-05 05:00:08
categories: arXiv_RO
tags: arXiv_RO Reinforcement_Learning CNN
author: Sai Krishna, Keehong Seo, Dhaivat Bhatt, Vincent Mai, Krishna Murthy, Liam Paull
mathjax: true
---

* content
{:toc}

##### Abstract
Active localization is the problem of generating robot actions that allow it to maximally disambiguate its pose within a reference map. Traditional approaches to this use an information-theoretic criterion for action selection and hand-crafted perceptual models. In this work we propose an end-to-end differentiable method for learning to take informative actions that is trainable entirely in simulation and then transferable to real robot hardware with zero refinement. The system is composed of two modules: a convolutional neural network for perception, and a deep reinforcement learned planning module. We introduce a multi-scale approach to the learned perceptual model since the accuracy needed to perform action selection with reinforcement learning is much less than the accuracy needed for robot control. We demonstrate that the resulting system outperforms using the traditional approach for either perception or planning. We also demonstrate our approaches robustness to different map configurations and other nuisance parameters through the use of domain randomization in training. The code is also compatible with the OpenAI gym framework, as well as the Gazebo simulator.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.01669](http://arxiv.org/abs/1903.01669)

##### PDF
[http://arxiv.org/pdf/1903.01669](http://arxiv.org/pdf/1903.01669)

