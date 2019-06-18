---
layout: post
title: "Sample-Efficient Neural Architecture Search by Learning Action Space"
date: 2019-06-17 03:50:25
categories: arXiv_CV
tags: arXiv_CV
author: Linnan Wang, Saining Xie, Teng Li, Rodrigo Fonseca, Yuandong Tian
mathjax: true
---

* content
{:toc}

##### Abstract
Neural Architecture Search (NAS) has emerged as a promising technique for automatic neural network design. However, existing NAS approaches often utilize manually designed action space, which is not directly related to the performance metric to be optimized (e.g., accuracy). As a result, using manually designed action space to perform NAS often leads to sample-inefficient explorations of architectures and thus can be sub-optimal. In order to improve sample efficiency, this paper proposes Latent Action Neural Architecture Search (LaNAS) that learns the action space to recursively partition the architecture search space into regions, each with concentrated performance metrics (\emph{i.e.}, low variance). During the search phase, as different architecture search action sequences lead to regions of different performance, the search efficiency can be significantly improved by biasing towards the regions with good performance. On the largest NAS dataset NasBench-101, our experimental results demonstrated that LaNAS is 22x, 14.6x and 12.4x more sample-efficient than random search, regularized evolution, and Monte Carlo Tree Search (MCTS) respectively. When applied to the open domain, LaNAS finds an architecture that achieves SoTA 98.0% accuracy on CIFAR-10 and 75.0% top1 accuracy on ImageNet (mobile setting), after exploring only 6,000 architectures.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06832](http://arxiv.org/abs/1906.06832)

##### PDF
[http://arxiv.org/pdf/1906.06832](http://arxiv.org/pdf/1906.06832)

