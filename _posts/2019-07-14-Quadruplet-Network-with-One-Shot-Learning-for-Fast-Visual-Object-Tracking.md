---
layout: post
title: "Quadruplet Network with One-Shot Learning for Fast Visual Object Tracking"
date: 2019-07-14 11:26:12
categories: arXiv_CV
tags: arXiv_CV Tracking Object_Tracking Detection Relation
author: Xingping Dong, Jianbing Shen, Dongming Wu, Kan Guo, Xiaogang Jin, Fatih Porikli
mathjax: true
---

* content
{:toc}

##### Abstract
In the same vein of discriminative one-shot learning, Siamese networks allow recognizing an object from a single exemplar with the same class label. However, they do not take advantage of the underlying structure of the data and the relationship among the multitude of samples as they only rely on pairs of instances for training. In this paper, we propose a new quadruplet deep network to examine the potential connections among the training instances, aiming to achieve a more powerful representation. We design four shared networks that receive multi-tuple of instances as inputs and are connected by a novel loss function consisting of pair-loss and triplet-loss. According to the similarity metric, we select the most similar and the most dissimilar instances as the positive and negative inputs of triplet loss from each multi-tuple. We show that this scheme improves the training performance. Furthermore, we introduce a new weight layer to automatically select suitable combination weights, which will avoid the conflict between triplet and pair loss leading to worse performance. We evaluate our quadruplet framework by model-free tracking-by-detection of objects from a single initial exemplar in several Visual Object Tracking benchmarks. Our extensive experimental analysis demonstrates that our tracker achieves superior performance with a real-time processing speed of 78 frames-per-second (fps).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1705.07222](http://arxiv.org/abs/1705.07222)

##### PDF
[http://arxiv.org/pdf/1705.07222](http://arxiv.org/pdf/1705.07222)

