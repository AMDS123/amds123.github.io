---
layout: post
title: "Effective Multi-Query Expansions: Collaborative Deep Networks for Robust Landmark Retrieval"
date: 2017-01-18 10:48:00
categories: arXiv_CV
tags: arXiv_CV
author: Yang Wang, Xuemin Lin, Lin Wu, Wenjie Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Given a query photo issued by a user (q-user), the landmark retrieval is to return a set of photos with their landmarks similar to those of the query, while the existing studies on the landmark retrieval focus on exploiting geometries of landmarks for similarity matches between candidate photos and a query photo. We observe that the same landmarks provided by different users over social media community may convey different geometry information depending on the viewpoints and/or angles, and may subsequently yield very different results. In fact, dealing with the landmarks with \illshapes caused by the photography of q-users is often nontrivial and has seldom been studied. In this paper we propose a novel framework, namely multi-query expansions, to retrieve semantically robust landmarks by two steps. Firstly, we identify the top-$k$ photos regarding the latent topics of a query landmark to construct multi-query set so as to remedy its possible \illshape. For this purpose, we significantly extend the techniques of Latent Dirichlet Allocation. Then, motivated by the typical \emph{collaborative filtering} methods, we propose to learn a \emph{collaborative} deep networks based semantically, nonlinear and high-level features over the latent factor for landmark photo as the training set, which is formed by matrix factorization over \emph{collaborative} user-photo matrix regarding the multi-query set. The learned deep network is further applied to generate the features for all the other photos, meanwhile resulting into a compact multi-query set within such space. Extensive experiments are conducted on real-world social media data with both landmark photos together with their user information to show the superior performance over the existing methods.

##### Abstract (translated by Google)
给定由用户（q用户）发出的查询照片，地标检索将返回具有与查询类似的地标的一组照片，而关于地标检索的现有研究集中在利用地标的几何图形候选人照片和查询照片之间的匹配。我们观察到，不同的用户在社交媒体社区上提供的相同地标可能根据视点和/或角度传达不同的几何信息，并且可能随后产生非常不同的结果。实际上，处理由q用户摄影造成的“纹理”的地标往往是非常平凡的，而且很少被研究。在本文中，我们提出了一个新的框架，即多查询扩展，通过两个步骤来检索语义健壮的地标。首先，我们确定关于查询标志的潜在主题的顶部$ k $照片，以构建多查询集合，以便纠正其可能的形状。为此，我们大大扩展了潜在狄利克雷分配技术。然后，在典型的协作过滤方法的推动下，我们提出了基于语义，非线性和高层次特征的协作式深度网络学习方法，将地标照片的潜在因子作为训练集形成通过关于多查询集的\ emph {合作}用户照片矩阵的矩阵分解。学习深度网络被进一步应用于为所有其他照片生成特征，同时在这样的空间内产生紧凑的多查询集。对具有里程碑意义的照片和用户信息的真实世界的社交媒体数据进行了广泛的实验，以显示比现有方法更优越的性能。

##### URL
[https://arxiv.org/abs/1701.05003](https://arxiv.org/abs/1701.05003)

##### PDF
[https://arxiv.org/pdf/1701.05003](https://arxiv.org/pdf/1701.05003)

