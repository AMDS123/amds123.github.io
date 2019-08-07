---
layout: post
title: "Multi-view Deep Subspace Clustering Networks"
date: 2019-08-06 06:44:43
categories: arXiv_CV
tags: arXiv_CV Regularization CNN Deep_Learning Relation
author: Pengfei Zhu, Binyuan Hui, Changqing Zhang, Dawei Du, Longyin Wen, Qinghua Hu
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-view subspace clustering aims to discover the inherent structure by fusing multi-view complementary information. Most existing methods first extract multiple types of hand-crafted features and then learn a joint affinity matrix for clustering. The disadvantage lies in two aspects: 1) Multi-view relations are not embedded into feature learning. 2) The end-to-end learning manner of deep learning is not well used in multi-view clustering. To address the above issues, we propose a novel multi-view deep subspace clustering network (MvDSCN) by learning a multi-view self-representation matrix in an end-to-end manner. MvDSCN consists of two sub-networks, i.e., diversity network (Dnet) and universality network (Unet). A latent space is built upon deep convolutional auto-encoders and a self-representation matrix is learned in the latent space using a fully connected layer. Dnet learns view-specific self-representation matrices while Unet learns a common self-representation matrix for all views. To exploit the complementarity of multi-view representations, Hilbert Schmidt Independence Criterion (HSIC) is introduced as a diversity regularization, which can capture the non-linear and high-order inter-view relations. As different views share the same label space, the self-representation matrices of each view are aligned to the common one by a universality regularization. Experiments on both multi-feature and multi-modality learning validate the superiority of the proposed multi-view subspace clustering model.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01978](http://arxiv.org/abs/1908.01978)

##### PDF
[http://arxiv.org/pdf/1908.01978](http://arxiv.org/pdf/1908.01978)

