---
layout: post
title: "An ILP Solver for Multi-label MRFs with Connectivity Constraints"
date: 2018-03-20 09:43:47
categories: arXiv_CV
tags: arXiv_CV Segmentation Weakly_Supervised
author: Ruobing Shen, Eric Kendinibilir, Ismail Ben Ayed, Andrea Lodi, Andrea Tramontani, Gerhard Reinelt
mathjax: true
---

* content
{:toc}

##### Abstract
Integer Linear Programming (ILP) formulations of Markov random fields (MRFs) models with global connectivity priors were investigated previously in computer vision, e.g., \cite{globalinter,globalconn}. In these works, only Linear Programing (LP) relaxations \cite{globalinter,globalconn} or simplified versions \cite{graphcutbase} of the problem were solved. This paper investigates the ILP of multi-label MRF with exact connectivity priors via a branch-and-cut method, which provably finds globally optimal solutions. The method enforces connectivity priors iteratively by a cutting plane method, and provides feasible solutions with a guarantee on sub-optimality even if we terminate it earlier. The proposed ILP can be applied as a post-processing method on top of any existing multi-label segmentation approach. As it provides globally optimal solution, it can be used off-line to generate ground-truth labeling, which serves as quality check for any fast on-line algorithm. Furthermore, it can be used to generate ground-truth proposals for weakly supervised segmentation. We demonstrate the power and usefulness of our model by several experiments on the BSDS500 and PASCAL image dataset, as well as on medical images with trained probability maps.

##### Abstract (translated by Google)
先前在计算机视觉中研究了具有全局连接先验的马尔科夫随机场（MRF）模型的整数线性规划（ILP）公式，例如\ cite {globalinter，globalconn}。在这些作品中，只解决了线性编程（LP）弛豫问题\ cite {globalinter，globalconn}或简化版本\ cite {graphcutbase}。本文通过分支切割方法研究了具有精确连通性先验的多标签MRF的ILP，证明了全局最优解。该方法通过切割平面方法迭代地执行连接性前提，并且提供可行的解决方案以及次优性保证，即使我们早先终止它也是如此。建议的ILP可以作为任何现有的多标签分割方法之上的后处理方法来应用。由于它提供了全球最佳的解决方案，因此可以脱机使用，以生成地面真实标签，作为任何快速在线算法的质量检查。此外，它可以用来生成弱监督分割的地面实况提议。我们通过对BSDS500和PASCAL图像数据集进行多次实验，以及使用经过训练的概率图的医学图像来证明我们模型的强大功能和实用性。

##### URL
[http://arxiv.org/abs/1712.06020](http://arxiv.org/abs/1712.06020)

##### PDF
[http://arxiv.org/pdf/1712.06020](http://arxiv.org/pdf/1712.06020)

