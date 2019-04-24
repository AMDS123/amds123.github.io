---
layout: post
title: "Wasserstein-Fisher-Rao Document Distance"
date: 2019-04-23 13:11:40
categories: arXiv_CL
tags: arXiv_CL Classification
author: Zihao Wang, Datong Zhou, Yong Zhang, Hao Wu, Chenglong Bao
mathjax: true
---

* content
{:toc}

##### Abstract
As a fundamental problem of natural language processing, it is important to measure the distance between different documents. Among the existing methods, the Word Mover's Distance (WMD) has shown remarkable success in document semantic matching for its clear physical insight as a parameter-free model. However, WMD is essentially based on the classical Wasserstein metric, thus it often fails to robustly represent the semantic similarity between texts of different lengths. In this paper, we apply the newly developed Wasserstein-Fisher-Rao (WFR) metric from unbalanced optimal transport theory to measure the distance between different documents. The proposed WFR document distance maintains the great interpretability and simplicity as WMD. We demonstrate that the WFR document distance has significant advantages when comparing the texts of different lengths. In addition, an accelerated Sinkhorn based algorithm with GPU implementation has been developed for the fast computation of WFR distances. The KNN classification results on eight datasets have shown its clear improvement over WMD.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.10294](http://arxiv.org/abs/1904.10294)

##### PDF
[http://arxiv.org/pdf/1904.10294](http://arxiv.org/pdf/1904.10294)

