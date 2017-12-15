---
layout: post
title: "Rigid Slice-To-Volume Medical Image Registration through Markov Random Fields"
date: 2016-08-19 10:29:50
categories: arXiv_CV
tags: arXiv_CV Optimization Relation
author: Roque Porchetto (1), Franco Stramana (1), Nikos Paragios (2), Enzo Ferrante (2) ((1) UNICEN University, Tandil Argentina, (2) CVN, CentraleSupelec-INRIA, Universite Paris-Saclay, France)
mathjax: true
---

* content
{:toc}

##### Abstract
Rigid slice-to-volume registration is a challenging task, which finds application in medical imaging problems like image fusion for image guided surgeries and motion correction for volume reconstruction. It is usually formulated as an optimization problem and solved using standard continuous methods. In this paper, we discuss how this task be formulated as a discrete labeling problem on a graph. Inspired by previous works on discrete estimation of linear transformations using Markov Random Fields (MRFs), we model it using a pairwise MRF, where the nodes are associated to the rigid parameters, and the edges encode the relation between the variables. We compare the performance of the proposed method to a continuous formulation optimized using simplex, and we discuss how it can be used to further improve the accuracy of our approach. Promising results are obtained using a monomodal dataset composed of magnetic resonance images (MRI) of a beating heart.

##### Abstract (translated by Google)
刚体切片注册是一项具有挑战性的任务，可应用于图像引导手术的图像融合和体积重建的运动矫正等医学成像问题。通常将其制定为优化问题，并使用标准的连续方法来解决。在本文中，我们讨论如何将这个任务作为一个图形上的离散标签问题。受以前关于使用马尔科夫随机场（MRF）的线性变换的离散估计的作品的启发，我们使用成对的MRF对其进行建模，其中节点与刚性参数相关联，并且边缘编码变量之间的关系。我们将所提出方法的性能与使用单纯形法进行优化的连续公式进行比较，并讨论如何使用它来进一步提高我们方法的准确性。使用由跳动的心脏的磁共振图像（MRI）组成的单模式数据集获得有希望的结果。

##### URL
[https://arxiv.org/abs/1608.05562](https://arxiv.org/abs/1608.05562)

##### PDF
[https://arxiv.org/pdf/1608.05562](https://arxiv.org/pdf/1608.05562)

