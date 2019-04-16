---
layout: post
title: "Profile-guided memory optimization for deep neural networks"
date: 2018-04-26 11:42:39
categories: arXiv_CV
tags: arXiv_CV Optimization Inference
author: Taro Sekiyama, Takashi Imamichi, Haruki Imai, Rudy Raymond
mathjax: true
---

* content
{:toc}

##### Abstract
Recent years have seen deep neural networks (DNNs) becoming wider and deeper to achieve better performance in many applications of AI. Such DNNs however require huge amounts of memory to store weights and intermediate results (e.g., activations, feature maps, etc.) in propagation. This requirement makes it difficult to run the DNNs on devices with limited, hard-to-extend memory, degrades the running time performance, and restricts the design of network models. We address this challenge by developing a novel profile-guided memory optimization to efficiently and quickly allocate memory blocks during the propagation in DNNs. The optimization utilizes a simple and fast heuristic algorithm based on the two-dimensional rectangle packing problem. Experimenting with well-known neural network models, we confirm that our method not only reduces the memory consumption by up to $49.5\%$ but also accelerates training and inference by up to a factor of four thanks to the rapidity of the memory allocation and the ability to use larger mini-batch sizes.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1804.10001](https://arxiv.org/abs/1804.10001)

##### PDF
[https://arxiv.org/pdf/1804.10001](https://arxiv.org/pdf/1804.10001)

