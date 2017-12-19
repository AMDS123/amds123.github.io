---
layout: post
title: "An ILP Solver for Multi-label MRFS with Connectivity Constraints"
date: 2017-12-16 21:19:44
categories: arXiv_CV
tags: arXiv_CV Segmentation
author: Ruobing Shen, Eric Kendinibilir, Ismail Ben Ayed, Andrea Lodi, Andrea Tramontani, Gerhard Reinelt
mathjax: true
---

* content
{:toc}

##### Abstract
Integer Linear Programming (ILP) formulations of Markov random fields (MRFs) models with global connectivity priors were investigated previously in computer vision, e.g., \cite{globalinter,globalconn}. In these works, only Linear Programming (LP) relaxations \cite{globalinter,globalconn} or simplified versions \cite{graphcutbase} of the problem were solved. This paper investigates the ILP of multi-label MRF with exact connectivity priors via a branch-and-cut method, which provably finds globally optimal solutions. The method enforces connectivity priors iteratively by a cutting plane method, and provides feasible solutions with a guarantee on sub-optimality even if we terminate it earlier. The proposed ILP can also be applied as a post-processing method on top of any existing multi-label segmentation approach. We demonstrate the power and usefulness of our model by several experiments on the BSDS500 image dataset, as well as on medical images with trained probability maps.

##### Abstract (translated by Google)
先前在计算机视觉中研究了具有全局连通性先验的马尔可夫随机场（MRF）模型的整数线性规划（ILP）公式，例如\ cite {globalinter，globalconn}。在这些工作中，只解决了线性规划（LP）松弛\ cite {globalinter，globalconn}或简化版本\ cite {graphcutbase}的问题。本文通过分支切割法研究了具有精确连通性的多标签MRF的ILP，证明了全局最优解。该方法通过切割平面方法迭代地执行连接性前提，并且即使我们早先终止，也提供具有次优性保证的可行解。建议的ILP也可以作为任何现有的多标签分割方法之上的后处理方法来应用。我们通过对BSDS500图像数据集进行多次实验，以及使用受训概率图的医学图像，展示了我们的模型的功能和实用性。

##### URL
[http://arxiv.org/abs/1712.06020](http://arxiv.org/abs/1712.06020)

##### PDF
[http://arxiv.org/pdf/1712.06020](http://arxiv.org/pdf/1712.06020)

