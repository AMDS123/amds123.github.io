---
layout: post
title: "Deep Unsupervised Similarity Learning using Partially Ordered Sets"
date: 2017-04-11 12:39:41
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Classification Deep_Learning Relation
author: Miguel A Bautista, Artsiom Sanakoyeu, Björn Ommer
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised learning of visual similarities is of paramount importance to computer vision, particularly due to lacking training data for fine-grained similarities. Deep learning of similarities is often based on relationships between pairs or triplets of samples. Many of these relations are unreliable and mutually contradicting, implying inconsistencies when trained without supervision information that relates different tuples or triplets to each other. To overcome this problem, we use local estimates of reliable (dis-)similarities to initially group samples into compact surrogate classes and use local partial orders of samples to classes to link classes to each other. Similarity learning is then formulated as a partial ordering task with soft correspondences of all samples to classes. Adopting a strategy of self-supervision, a CNN is trained to optimally represent samples in a mutually consistent manner while updating the classes. The similarity learning and grouping procedure are integrated in a single model and optimized jointly. The proposed unsupervised approach shows competitive performance on detailed pose estimation and object classification.

##### Abstract (translated by Google)
视觉相似性的无监督学习对于计算机视觉至关重要，特别是由于缺乏精细相似的训练数据。相似之处的深入学习通常是基于样本对或三元组之间的关系。这些关系中的许多是不可靠的，相互矛盾的，这意味着在没有监督信息的情况下训练不一致，这些信息将不同的元组或三元组联系起来。为了克服这个问题，我们使用局部可靠（不相似）相似性估计来初始将样本组合成紧凑的替代类，并且使用局部样本类的部分顺序来将类彼此连接起来。然后将相似性学习作为一个部分排序任务，并将所有样本与软件对应起来。采用一种自我监督的策略，CNN被训练成在更新课程的同时以相互一致的方式最优化地表示样本。相似性学习和分组程序被集成在一个单一的模型中，并被联合优化。所提出的无监督方法在详细的姿态估计和对象分类上显示出竞争性的表现。

##### URL
[https://arxiv.org/abs/1704.02268](https://arxiv.org/abs/1704.02268)

##### PDF
[https://arxiv.org/pdf/1704.02268](https://arxiv.org/pdf/1704.02268)

