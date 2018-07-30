---
layout: post
title: "Saliency Integration: An Arbitrator Model"
date: 2018-07-27 12:41:34
categories: arXiv_CV
tags: arXiv_CV Salient Knowledge Attention Face Deep_Learning
author: Yingyue Xu, Xiaopeng Hong, Fatih Porikli, Xin Liu, Jie Chen, Guoying Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
Saliency integration has attracted much attention on unifying saliency maps from multiple saliency models. Previous offline integration methods usually face two challenges: 1. if most of the candidate saliency models misjudge the saliency on an image, the integration result will lean heavily on those inferior candidate models; 2. an unawareness of the ground truth saliency labels brings difficulty in estimating the expertise of each candidate model. To address these problems, in this paper, we propose an arbitrator model (AM) for saliency integration. Firstly, we incorporate the consensus of multiple saliency models and the external knowledge into a reference map to effectively rectify the misleading by candidate models. Secondly, our quest for ways of estimating the expertise of the saliency models without ground truth labels gives rise to two distinct online model-expertise estimation methods. Finally, we derive a Bayesian integration framework to reconcile the saliency models of varying expertise and the reference map. To extensively evaluate the proposed AM model, we test twenty-seven state-of-the-art saliency models, covering both traditional and deep learning ones, on various combinations over four datasets. The evaluation results show that the AM model improves the performance substantially compared to the existing state-of-the-art integration methods, regardless of the chosen candidate saliency models.

##### Abstract (translated by Google)
显着性整合吸引了很多关注统一来自多个显着性模型的显着性图。以前的离线整合方法通常面临两个挑战：1。如果大多数候选显着性模型误判了图像上的显着性，那么整合结果将严重依赖于那些劣质候选模型; 2.不了解真实显着性标签会给每个候选模型的专业知识带来困难。为了解决这些问题，在本文中，我们提出了一种用于显着性整合的仲裁模型（AM）。首先，我们将多个显着性模型和外部知识的共识纳入参考图，以有效地纠正候选模型的误导。其次，我们寻求在没有地面真实标签的情况下估算显着性模型的专业知识的方法，产生了两种不同的在线模型 - 专业知识估计方法。最后，我们推导出一个贝叶斯积分框架，以协调不同专业知识和参考图的显着性模型。为了广泛评估所提出的AM模型，我们在四个数据集上的各种组合上测试了二十七个最先进的显着性模型，包括传统和深度学习模型。评估结果表明，与现有的最先进的集成方法相比，AM模型大大提高了性能，无论选择的候选显着性模型如何。

##### URL
[http://arxiv.org/abs/1608.01536](http://arxiv.org/abs/1608.01536)

##### PDF
[http://arxiv.org/pdf/1608.01536](http://arxiv.org/pdf/1608.01536)

