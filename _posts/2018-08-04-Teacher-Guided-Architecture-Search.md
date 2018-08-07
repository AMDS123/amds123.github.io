---
layout: post
title: "Teacher Guided Architecture Search"
date: 2018-08-04 01:43:03
categories: arXiv_CV
tags: arXiv_CV CNN
author: Pouya Bashivan, Mark Tensen, James J DiCarlo
mathjax: true
---

* content
{:toc}

##### Abstract
Strong improvements in network performance in vision tasks have resulted from the search of alternative network architectures, and prior work has shown that this search process can be automated and guided by evaluating candidate network performance following limited training (Performance Guided Architecture Search or PGAS). However, because of the large architecture search spaces and the high computational cost associated with evaluating each candidate model, further gains in computational efficiency are needed. Here we present a method termed Teacher Guided Search for Architectures by Generation and Evaluation (TG-SAGE) that produces up to an order of magnitude in search efficiency over PGAS methods. Specifically, TG-SAGE guides each step of the architecture search by evaluating the similarity of internal representations of the candidate networks with those of the (fixed) teacher network. We show that this procedure leads to significant reduction in required per-sample training and that, this advantage holds for two different search spaces of architectures, and two different search algorithms. We further show that in the space of convolutional cells for visual categorization, TG-SAGE finds a cell structure with similar performance as was previously found using other methods but at a total computational cost that is two orders of magnitude lower than Neural Architecture Search (NAS) and more than four times lower than progressive neural architecture search (PNAS). These results suggest that TG-SAGE can be used to accelerate network architecture search in cases where one has access to some or all of the internal representations of a teacher network of interest, such as the brain.

##### Abstract (translated by Google)
搜索替代网络架构导致视觉任务中网络性能的显着改善，并且先前的工作已经表明，通过在有限培训（性能引导架构搜索或PGAS）之后评估候选网络性能，可以自动化和指导该搜索过程。然而，由于大型架构搜索空间和与评估每个候选模型相关联的高计算成本，因此需要进一步提高计算效率。在这里，我们提出了一种方法，称为教师引导搜索生成和评估架构（TG-SAGE），与PGAS方法相比，可以产生高达一个数量级的搜索效率。具体而言，TG-SAGE通过评估候选网络的内部表示与（固定）教师网络的内部表示的相似性来指导体系结构搜索的每个步骤。我们表明，该过程可以显着减少所需的每个样本培训，并且这个优势适用于两个不同的体系结构搜索空间和两个不同的搜索算法。我们进一步表明，在用于视觉分类的卷积细胞空间中，TG-SAGE发现具有与先前使用其他方法发现的相似性能的细胞结构，但总计算成本比神经架构搜索（NAS）低两个数量级。并且比渐进式神经结构搜索（PNAS）低四倍以上。这些结果表明，在人们可以访问感兴趣的教师网络（如大脑）的部分或全部内部表示的情况下，TG-SAGE可用于加速网络架构搜索。

##### URL
[https://arxiv.org/abs/1808.01405](https://arxiv.org/abs/1808.01405)

##### PDF
[https://arxiv.org/pdf/1808.01405](https://arxiv.org/pdf/1808.01405)

