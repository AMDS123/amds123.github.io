---
layout: post
title: "Learn from Your Neighbor: Learning Multi-modal Mappings from Sparse Annotations"
date: 2018-06-08 01:18:10
categories: arXiv_CV
tags: arXiv_CV Sparse Caption Classification Prediction
author: Ashwin Kalyan, Stefan Lee, Anitha Kannan, Dhruv Batra
mathjax: true
---

* content
{:toc}

##### Abstract
Many structured prediction problems (particularly in vision and language domains) are ambiguous, with multiple outputs being correct for an input - e.g. there are many ways of describing an image, multiple ways of translating a sentence; however, exhaustively annotating the applicability of all possible outputs is intractable due to exponentially large output spaces (e.g. all English sentences). In practice, these problems are cast as multi-class prediction, with the likelihood of only a sparse set of annotations being maximized - unfortunately penalizing for placing beliefs on plausible but unannotated outputs. We make and test the following hypothesis - for a given input, the annotations of its neighbors may serve as an additional supervisory signal. Specifically, we propose an objective that transfers supervision from neighboring examples. We first study the properties of our developed method in a controlled toy setup before reporting results on multi-label classification and two image-grounded sequence modeling tasks - captioning and question generation. We evaluate using standard task-specific metrics and measures of output diversity, finding consistent improvements over standard maximum likelihood training and other baselines.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1806.02934](https://arxiv.org/abs/1806.02934)

##### PDF
[https://arxiv.org/pdf/1806.02934](https://arxiv.org/pdf/1806.02934)

