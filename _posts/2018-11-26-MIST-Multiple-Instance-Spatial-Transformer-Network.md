---
layout: post
title: "MIST: Multiple Instance Spatial Transformer Network"
date: 2018-11-26 22:49:20
categories: arXiv_CV
tags: arXiv_CV Knowledge Optimization Classification Detection
author: Baptiste Angles, Shahram Izadi, Andrea Tagliasacchi, Kwang Moo Yi
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a deep network that can be trained to tackle image reconstruction and classification problems that involve detection of multiple object instances, without any supervision regarding their whereabouts. The network learns to extract the most significant top-K patches, and feeds these patches to a task-specific network -- e.g., auto-encoder or classifier -- to solve a domain specific problem. The challenge in training such a network is the non-differentiable top-K selection process. To address this issue, we lift the training optimization problem by treating the result of top-K selection as a slack variable, resulting in a simple, yet effective, multi-stage training. Our method is able to learn to detect recurrent structures in the training dataset by learning to reconstruct images. It can also learn to localize structures when only knowledge on the occurrence of the object is provided, and in doing so it outperforms the state-of-the-art.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.10725](http://arxiv.org/abs/1811.10725)

##### PDF
[http://arxiv.org/pdf/1811.10725](http://arxiv.org/pdf/1811.10725)

