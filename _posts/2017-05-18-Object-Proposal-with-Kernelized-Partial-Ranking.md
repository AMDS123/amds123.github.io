---
layout: post
title: "Object Proposal with Kernelized Partial Ranking"
date: 2017-05-18 15:57:36
categories: arXiv_CV
tags: arXiv_CV
author: Jing Wang, Jie Shen, Ping Li
mathjax: true
---

* content
{:toc}

##### Abstract
Object proposals are an ensemble of bounding boxes with high potential to contain objects. In order to determine a small set of proposals with a high recall, a common scheme is extracting multiple features followed by a ranking algorithm which however, incurs two major challenges: {\bf 1)} The ranking model often imposes pairwise constraints between each proposal, rendering the problem away from an efficient training/testing phase; {\bf 2)} Linear kernels are utilized due to the computational and memory bottleneck of training a kernelized model. In this paper, we remedy these two issues by suggesting a {\em kernelized partial ranking model}. In particular, we demonstrate that {\bf i)} our partial ranking model reduces the number of constraints from $O(n^2)$ to $O(nk)$ where $n$ is the number of all potential proposals for an image but we are only interested in top-$k$ of them that has the largest overlap with the ground truth; {\bf ii)} we permit non-linear kernels in our model which is often superior to the linear classifier in terms of accuracy. For the sake of mitigating the computational and memory issues, we introduce a consistent weighted sampling~(CWS) paradigm that approximates the non-linear kernel as well as facilitates an efficient learning. In fact, as we will show, training a linear CWS model amounts to learning a kernelized model. Extensive experiments demonstrate that equipped with the non-linear kernel and the partial ranking algorithm, recall at top-$k$ proposals can be substantially improved.

##### Abstract (translated by Google)
对象提议是包含对象的高度可能性的边界框的集合。为了确定一个召回率较高的提案，一个共同的方案是提取多个特征，然后是一个排序算法，然而，这个算法会带来两个主要的挑战：排名模型通常会在每个提案之间施加成对的约束，使问题远离有效的培训/测试阶段; {\ bf 2）}由于训练内核化模型的计算和内存瓶颈，使用线性内核。在本文中，我们通过建议{\ em核化的部分排名模型}来解决这两个问题。特别地，我们证明{\ bf i）}我们的部分排名模型将约束从$ O（n ^ 2）$减少到$ O（nk）$，其中$ n $是所有可能的提议的数量形象，但我们只关注其中与地面事实有最大重叠的顶部$ k $; {\ bf ii）}我们允许我们的模型中的非线性核，在精度方面经常优于线性分类器。为了减轻计算和存储的问题，我们引入了一个一致的加权采样（CWS）范式，它近似于非线性内核，并且有助于高效的学习。事实上，正如我们将要展示的那样，训练一个线性CWS模型就等于学习一个核心模型。大量的实验表明，配备非线性核和部分排序算法，可以大幅度提高顶部$ k $建议的回忆。

##### URL
[https://arxiv.org/abs/1502.01526](https://arxiv.org/abs/1502.01526)

##### PDF
[https://arxiv.org/pdf/1502.01526](https://arxiv.org/pdf/1502.01526)

