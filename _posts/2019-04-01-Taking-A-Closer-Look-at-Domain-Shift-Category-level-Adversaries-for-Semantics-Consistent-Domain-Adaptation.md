---
layout: post
title: "Taking A Closer Look at Domain Shift: Category-level Adversaries for Semantics Consistent Domain Adaptation"
date: 2019-04-01 14:25:06
categories: arXiv_AI
tags: arXiv_AI Adversarial Segmentation Semantic_Segmentation
author: Yawei Luo, Liang Zheng, Tao Guan, Junqing Yu, Yi Yang
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of unsupervised domain adaptation in semantic segmentation. The key in this campaign consists in reducing the domain shift, i.e., enforcing the data distributions of the two domains to be similar. A popular strategy is to align the marginal distribution in the feature space through adversarial learning. However, this global alignment strategy does not consider the local category-level feature distribution. A possible consequence of the global movement is that some categories which are originally well aligned between the source and target may be incorrectly mapped. To address this problem, this paper introduces a category-level adversarial network, aiming to enforce local semantic consistency during the trend of global alignment. Our idea is to take a close look at the category-level data distribution and align each class with an adaptive adversarial loss. Specifically, we reduce the weight of the adversarial loss for category-level aligned features while increasing the adversarial force for those poorly aligned. In this process, we decide how well a feature is category-level aligned between source and target by a co-training approach. In two domain adaptation tasks, i.e., GTA5 -&gt; Cityscapes and SYNTHIA -&gt; Cityscapes, we validate that the proposed method matches the state of the art in segmentation accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.09478](http://arxiv.org/abs/1809.09478)

##### PDF
[http://arxiv.org/pdf/1809.09478](http://arxiv.org/pdf/1809.09478)

