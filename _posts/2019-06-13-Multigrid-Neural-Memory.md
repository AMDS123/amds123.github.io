---
layout: post
title: "Multigrid Neural Memory"
date: 2019-06-13 22:10:01
categories: arXiv_CV
tags: arXiv_CV GAN CNN
author: Tri Huynh, Michael Maire, Matthew R. Walter
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a novel architecture that integrates a large addressable memory space into the core functionality of a deep neural network. Our design distributes both memory addressing operations and storage capacity over many network layers. Distinct from strategies that connect neural networks to external memory banks, our approach co-locates memory with computation throughout the network structure. Mirroring recent architectural innovations in convolutional networks, we organize memory into a multiresolution hierarchy, whose internal connectivity enables learning of dynamic information routing strategies and data-dependent read/write operations. This multigrid spatial layout permits parameter-efficient scaling of memory size, allowing us to experiment with memories substantially larger than those in prior work. We demonstrate this capability on synthetic exploration and mapping tasks, where the network is able to self-organize and retain long-term memory for trajectories of thousands of time steps. On tasks decoupled from any notion of spatial geometry, such as sorting or associative recall, our design functions as a truly generic memory and yields results competitive with those of the recently proposed Differentiable Neural Computer.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.05948](https://arxiv.org/abs/1906.05948)

##### PDF
[https://arxiv.org/pdf/1906.05948](https://arxiv.org/pdf/1906.05948)

