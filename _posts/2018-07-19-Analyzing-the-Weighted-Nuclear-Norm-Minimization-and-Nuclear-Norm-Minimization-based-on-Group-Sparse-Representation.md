---
layout: post
title: "Analyzing the Weighted Nuclear Norm Minimization and Nuclear Norm Minimization based on Group Sparse Representation"
date: 2018-07-19 03:11:49
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Zhiyuan Zha, Xin Yuan, Bei Li, Xinggan Zhang, Xin Liu, Lan Tang, Ying-Chang Liang
mathjax: true
---

* content
{:toc}

##### Abstract
Rank minimization methods have attracted considerable interest in various areas, such as computer vision and machine learning. The most representative work is nuclear norm minimization (NNM), which can recover the matrix rank exactly under some restricted and theoretical guarantee conditions. However, for many real applications, NNM is not able to approximate the matrix rank accurately, since it often tends to over-shrink the rank components. To rectify the weakness of NNM, recent advances have shown that weighted nuclear norm minimization (WNNM) can achieve a better matrix rank approximation than NNM, which heuristically set the weight being inverse to the singular values. However, it still lacks a sound mathematical explanation on why WNNM is more feasible than NNM. In this paper, we propose a scheme to analyze WNNM and NNM from the perspective of the group sparse representation. Specifically, we design an adaptive dictionary to bridge the gap between the group sparse representation and the rank minimization models. Based on this scheme, we provide a mathematical derivation to explain why WNNM is more feasible than NNM. Moreover, due to the heuristical set of the weight, WNNM sometimes pops out error in the operation of SVD, and thus we present an adaptive weight setting scheme to avoid this error. We then employ the proposed scheme on two low-level vision tasks including image denoising and image inpainting. Experimental results demonstrate that WNNM is more feasible than NNM and the proposed scheme outperforms many current state-of-the-art methods.

##### Abstract (translated by Google)
秩最小化方法已经在诸如计算机视觉和机器学习的各个领域引起了相当大的兴趣。最具代表性的工作是核规范最小化（NNM），它可以在一些限制和理论保证条件下准确地恢复矩阵秩。然而，对于许多实际应用，NNM不能准确地近似矩阵秩，因为它经常倾向于过度缩减秩组件。为了纠正NNM的弱点，最近的进展表明，加权核范数最小化（WNNM）可以实现比NNM更好的矩阵秩近似，其启发式地将权重设置为与奇异值相反。然而，对于为什么WNNM比NNM更可行，它仍然缺乏合理的数学解释。在本文中，我们提出了一种从群体稀疏表示的角度分析WNNM和NNM的方案。具体来说，我们设计了一个自适应字典来弥合组稀疏表示和秩最小化模型之间的差距。基于该方案，我们提供了一个数学推导来解释为什么WNNM比NNM更可行。此外，由于权重的启发式设置，WNNM有时会在SVD的操作中弹出错误，因此我们提出了一种自适应权重设置方案来避免这种错误。然后，我们将所提出的方案应用于两个低级视觉任务，包括图像去噪和图像修复。实验结果表明，WNNM比NNM更可行，并且所提出的方案优于许多当前最先进的方法。

##### URL
[http://arxiv.org/abs/1702.04463](http://arxiv.org/abs/1702.04463)

##### PDF
[http://arxiv.org/pdf/1702.04463](http://arxiv.org/pdf/1702.04463)

