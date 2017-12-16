---
layout: post
title: "Learning an Invariant Hilbert Space for Domain Adaptation"
date: 2017-04-17 09:12:00
categories: arXiv_CV
tags: arXiv_CV Optimization Classification
author: Samitha Herath, Mehrtash Harandi, Fatih Porikli
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces a learning scheme to construct a Hilbert space (i.e., a vector space along its inner product) to address both unsupervised and semi-supervised domain adaptation problems. This is achieved by learning projections from each domain to a latent space along the Mahalanobis metric of the latent space to simultaneously minimizing a notion of domain variance while maximizing a measure of discriminatory power. In particular, we make use of the Riemannian optimization techniques to match statistical properties (e.g., first and second order statistics) between samples projected into the latent space from different domains. Upon availability of class labels, we further deem samples sharing the same label to form more compact clusters while pulling away samples coming from different classes.We extensively evaluate and contrast our proposal against state-of-the-art methods for the task of visual domain adaptation using both handcrafted and deep-net features. Our experiments show that even with a simple nearest neighbor classifier, the proposed method can outperform several state-of-the-art methods benefitting from more involved classification schemes.

##### Abstract (translated by Google)
本文引入了一个学习方案来构造一个Hilbert空间（即沿其内积的向量空间）来解决无监督和半监督的领域自适应问题。这是通过学习从每个领域到潜在空间的马哈拉诺比斯度量的潜在空间的投影来实现的，同时最小化领域差异的概念，同时最大化区分能力的度量。具体而言，我们利用黎曼优化技术来匹配投影到来自不同域的潜在空间的样本之间的统计特性（例如，一阶和二阶统计量）。根据类标签的可用性，我们进一步认为共享相同标签的样本形成更紧凑的群集，同时从不同类别中抽取样本。我们广泛评估和对比了我们的建议与针对视觉领域任务的最新方法使用手工和深网功能进行适应。我们的实验表明，即使是一个简单的最近邻分类器，所提出的方法可以超越几个最先进的方法受益于更多的涉及分类方案。

##### URL
[https://arxiv.org/abs/1611.08350](https://arxiv.org/abs/1611.08350)

##### PDF
[https://arxiv.org/pdf/1611.08350](https://arxiv.org/pdf/1611.08350)

