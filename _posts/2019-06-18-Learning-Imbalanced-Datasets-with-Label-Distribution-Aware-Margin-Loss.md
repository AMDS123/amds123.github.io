---
layout: post
title: "Learning Imbalanced Datasets with Label-Distribution-Aware Margin Loss"
date: 2019-06-18 07:21:18
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Kaidi Cao, Colin Wei, Adrien Gaidon, Nikos Arechiga, Tengyu Ma
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning algorithms can fare poorly when the training dataset suffers from heavy class-imbalance but the testing criterion requires good generalization on less frequent classes. We design two novel methods to improve performance in such scenarios. First, we propose a theoretically-principled label-distribution-aware margin (LDAM) loss motivated by minimizing a margin-based generalization bound. This loss replaces the standard cross-entropy objective during training and can be applied with prior strategies for training with class-imbalance such as re-weighting or re-sampling. Second, we propose a simple, yet effective, training schedule that defers re-weighting until after the initial stage, allowing the model to learn an initial representation while avoiding some of the complications associated with re-weighting or re-sampling. We test our methods on several benchmark vision tasks including the real-world imbalanced dataset iNaturalist 2018. Our experiments show that either of these methods alone can already improve over existing techniques and their combination achieves even better performance gains.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.07413](http://arxiv.org/abs/1906.07413)

##### PDF
[http://arxiv.org/pdf/1906.07413](http://arxiv.org/pdf/1906.07413)

