---
layout: post
title: "Multi-Focus Image Fusion Via Coupled Sparse Representation and Dictionary Learning"
date: 2017-05-30 12:20:26
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Rui Gao, Sergiy A. Vorobyov
mathjax: true
---

* content
{:toc}

##### Abstract
We address the multi-focus image fusion problem, where multiple images captured with different focal settings are to be fused into an all-in-focus image of higher quality. Algorithms for this problem necessarily admit the source image characteristics along with focused and blurred feature. However, most sparsity-based approaches use a single dictionary in focused feature space to describe multi-focus images, and ignore the representations in blurred feature space. Here, we propose a multi-focus image fusion approach based on coupled sparse representation. The approach exploits the facts that (i) the patches in given training set can be sparsely represented by a couple of overcomplete dictionaries related to the focused and blurred categories of images; and (ii) merging such representations leads to a more flexible and therefore better fusion strategy than the one based on just selecting the sparsest representation in the original image estimate. By jointly learning the coupled dictionary, we enforce the similarity of sparse representations in the focused and blurred feature spaces, and then introduce a fusion approach to combine these representations for generating an all-in-focus image. We also discuss the advantages of the fusion approach based on coupled sparse representation and present an efficient algorithm for learning the coupled dictionary. Extensive experimental comparisons with state-of-the-art multi-focus image fusion algorithms validate the effectiveness of the proposed approach.

##### Abstract (translated by Google)
我们解决了多焦点图像融合问题，即用不同焦点设置拍摄的多个图像将融合成更高质量的全焦点图像。针对这个问题的算法必须承认源图像特征以及聚焦和模糊的特征。然而，大多数基于稀疏性的方法都是使用聚焦特征空间中的单个词典来描述多聚焦图像，而忽略模糊特征空间中的表示。在这里，我们提出了基于耦合稀疏表示的多焦点图像融合方法。该方法利用了以下事实：（i）给定训练集中的补丁可以由与图像的聚焦和模糊类别相关的几个完整字典稀疏地表示; （ii）合并这样的表示导致比仅基于在原始图像估计中选择最稀疏表示的那个更加灵活并因此更好的融合策略。通过联合学习耦合词典，强化稀疏表示在聚焦和模糊特征空间中的相似性，然后引入融合方法来组合这些表示，以生成全焦点图像。本文还讨论了基于耦合稀疏表示的融合方法的优点，提出了一种有效的耦合词典学习算法。使用最先进的多焦点图像融合算法进行广泛的实验比较验证了所提出方法的有效性。

##### URL
[https://arxiv.org/abs/1705.10574](https://arxiv.org/abs/1705.10574)

##### PDF
[https://arxiv.org/pdf/1705.10574](https://arxiv.org/pdf/1705.10574)

