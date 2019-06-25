---
layout: post
title: "Densely Connected Search Space for More Flexible Neural Architecture Search"
date: 2019-06-23 16:49:40
categories: arXiv_CV
tags: arXiv_CV
author: Jiemin Fang, Yuzhu Sun, Qian Zhang, Yuan Li, Wenyu Liu, Xinggang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, neural architecture search (NAS) has dramatically advanced the development of neural network design. While most previous works are computationally intensive, differentiable NAS methods reduce the search cost by constructing a super network in a continuous space covering all possible architectures to search for. However, few of them can search for the network width (the number of filters/channels) because it is intractable to integrate architectures with different widths into one super network following conventional differentiable NAS paradigm. In this paper, we propose a novel differentiable NAS method which can search for the width and the spatial resolution of each block simultaneously. We achieve this by constructing a densely connected search space and name our method as DenseNAS. Blocks with different width and spatial resolution combinations are densely connected to each other. The best path in the super network is selected by optimizing the transition probabilities between blocks. As a result, the overall depth distribution of the network is optimized globally in a graceful manner. In the experiments, DenseNAS obtains an architecture with 75.9% top-1 accuracy on ImageNet and the latency is as low as 24.3ms on a single TITAN-XP. The total search time is merely 23 hours on 4 GPUs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.09607](http://arxiv.org/abs/1906.09607)

##### PDF
[http://arxiv.org/pdf/1906.09607](http://arxiv.org/pdf/1906.09607)

