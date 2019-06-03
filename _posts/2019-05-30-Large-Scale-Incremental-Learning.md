---
layout: post
title: "Large Scale Incremental Learning"
date: 2019-05-30 18:51:39
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Yue Wu, Yinpeng Chen, Lijuan Wang, Yuancheng Ye, Zicheng Liu, Yandong Guo, Yun Fu
mathjax: true
---

* content
{:toc}

##### Abstract
Modern machine learning suffers from catastrophic forgetting when learning new classes incrementally. The performance dramatically degrades due to the missing data of old classes. Incremental learning methods have been proposed to retain the knowledge acquired from the old classes, by using knowledge distilling and keeping a few exemplars from the old classes. However, these methods struggle to scale up to a large number of classes. We believe this is because of the combination of two factors: (a) the data imbalance between the old and new classes, and (b) the increasing number of visually similar classes. Distinguishing between an increasing number of visually similar classes is particularly challenging, when the training data is unbalanced. We propose a simple and effective method to address this data imbalance issue. We found that the last fully connected layer has a strong bias towards the new classes, and this bias can be corrected by a linear model. With two bias parameters, our method performs remarkably well on two large datasets: ImageNet (1000 classes) and MS-Celeb-1M (10000 classes), outperforming the state-of-the-art algorithms by 11.1% and 13.2% respectively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.13260](http://arxiv.org/abs/1905.13260)

##### PDF
[http://arxiv.org/pdf/1905.13260](http://arxiv.org/pdf/1905.13260)

