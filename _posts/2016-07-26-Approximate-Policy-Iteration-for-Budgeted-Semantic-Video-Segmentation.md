---
layout: post
title: "Approximate Policy Iteration for Budgeted Semantic Video Segmentation"
date: 2016-07-26 15:58:32
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Inference Classification
author: Behrooz Mahasseni, Sinisa Todorovic, Alan Fern
mathjax: true
---

* content
{:toc}

##### Abstract
This paper formulates and presents a solution to the new problem of budgeted semantic video segmentation. Given a video, the goal is to accurately assign a semantic class label to every pixel in the video within a specified time budget. Typical approaches to such labeling problems, such as Conditional Random Fields (CRFs), focus on maximizing accuracy but do not provide a principled method for satisfying a time budget. For video data, the time required by CRF and related methods is often dominated by the time to compute low-level descriptors of supervoxels across the video. Our key contribution is the new budgeted inference framework for CRF models that intelligently selects the most useful subsets of descriptors to run on subsets of supervoxels within the time budget. The objective is to maintain an accuracy as close as possible to the CRF model with no time bound, while remaining within the time budget. Our second contribution is the algorithm for learning a policy for the sparse selection of supervoxels and their descriptors for budgeted CRF inference. This learning algorithm is derived by casting our problem in the framework of Markov Decision Processes, and then instantiating a state-of-the-art policy learning algorithm known as Classification-Based Approximate Policy Iteration. Our experiments on multiple video datasets show that our learning approach and framework is able to significantly reduce computation time, and maintain competitive accuracy under varying budgets.

##### Abstract (translated by Google)
本文针对预算语义视频分割的新问题提出并提出了解决方案。给定视频，目标是在指定的时间预算内为视频中的每个像素准确分配语义类标签。这种标签问题的典型方法，如条件随机场（CRF），注重最大化准确性，但不提供满足时间预算的原则性方法。对于视频数据，CRF和相关方法所需的时间通常由计算视频中超级像素的低级描述符的时间来控制。我们的主要贡献是CRF模型的新的预算推理框架，智能地选择描述符的最有用的子集在时间预算内在超体素的子集上运行。目标是保持尽可能接近CRF模型的准确性，不受时间限制，同时保持在时间预算内。我们的第二个贡献是用于学习稀疏选择超体素及其描述符用于预算CRF推断的策略的算法。这个学习算法是通过在马尔科夫决策过程的框架中施加我们的问题得到的，然后实例化一种称为基于分类的近似策略迭代的最先进的策略学习算法。我们对多个视频数据集的实验表明，我们的学习方法和框架能够显着减少计算时间，并在变化的预算下保持竞争的准确性。

##### URL
[https://arxiv.org/abs/1607.07770](https://arxiv.org/abs/1607.07770)

##### PDF
[https://arxiv.org/pdf/1607.07770](https://arxiv.org/pdf/1607.07770)

