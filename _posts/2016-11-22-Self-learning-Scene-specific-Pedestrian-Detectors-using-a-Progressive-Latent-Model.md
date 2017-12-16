---
layout: post
title: "Self-learning Scene-specific Pedestrian Detectors using a Progressive Latent Model"
date: 2016-11-22 21:33:07
categories: arXiv_CV
tags: arXiv_CV Regularization Object_Detection Weakly_Supervised Transfer_Learning Detection
author: Qixiang Ye, Tianliang Zhang, Qiang Qiu, Baochang Zhang, Jie Chen, Guillermo Sapiro
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, a self-learning approach is proposed towards solving scene-specific pedestrian detection problem without any human' annotation involved. The self-learning approach is deployed as progressive steps of object discovery, object enforcement, and label propagation. In the learning procedure, object locations in each frame are treated as latent variables that are solved with a progressive latent model (PLM). Compared with conventional latent models, the proposed PLM incorporates a spatial regularization term to reduce ambiguities in object proposals and to enforce object localization, and also a graph-based label propagation to discover harder instances in adjacent frames. With the difference of convex (DC) objective functions, PLM can be efficiently optimized with a concave-convex programming and thus guaranteeing the stability of self-learning. Extensive experiments demonstrate that even without annotation the proposed self-learning approach outperforms weakly supervised learning approaches, while achieving comparable performance with transfer learning and fully supervised approaches.

##### Abstract (translated by Google)
在本文中，提出了一种自主学习的方法来解决场景特定的行人检测问题，而不涉及任何人的注释。自学习方法被部署为对象发现，对象强制和标签传播的渐进式步骤。在学习过程中，每个框架中的对象位置被视为用渐进式潜在模型（PLM）解决的潜在变量。与传统的潜在模型相比，所提出的PLM结合了一个空间正则化术语来减少对象提议中的模糊性，并且强化对象本地化，并且还实现了基于图的标签传播以发现相邻帧中的较难实例。随着凸（DC）目标函数的不同，PLM可以通过凹凸规划进行高效优化，从而保证了自学习的稳定性。大量的实验表明，即使没有注释，提出的自学习方法胜过弱监督学习方法，同时实现与转移学习和完全监督方法相当的性能。

##### URL
[https://arxiv.org/abs/1611.07544](https://arxiv.org/abs/1611.07544)

##### PDF
[https://arxiv.org/pdf/1611.07544](https://arxiv.org/pdf/1611.07544)

