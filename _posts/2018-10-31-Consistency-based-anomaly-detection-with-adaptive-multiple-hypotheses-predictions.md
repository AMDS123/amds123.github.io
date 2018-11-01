---
layout: post
title: "Consistency-based anomaly detection with adaptive multiple-hypotheses predictions"
date: 2018-10-31 14:05:44
categories: arXiv_AI
tags: arXiv_AI Classification Prediction Detection
author: Duc Tam Nguyen, Zhongyu Lou, Michael Klar, Thomas Brox
mathjax: true
---

* content
{:toc}

##### Abstract
In out-of-distribution classification tasks, only some classes - the normal cases - can be modeled with data, whereas the variation of all possible anomalies is too large to be described sufficiently by samples. Thus, the wide-spread discriminative approaches cannot cover such learning tasks and rather generative models, which attempt to learn the input density of the ordinary cases, are used. However, generative models suffer under a large input dimensionality (as in images) and are typically inefficient learners. Motivated by the Local-Outlier-Factor (LOF) method, in this work, we propose to allow the network to directly estimate the local density functions since, for the detection of outliers, the local neighborhood is more important than the global one. At the same time, we retain consistency in the sense that the model must not support areas of the input space that are not covered by samples. Our method allows the model to identify out-of-distribution samples reliably. For the anomaly detection task on CIFAR-10, our ConAD model results in up to 5% points improvement over previously reported results.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.13292](http://arxiv.org/abs/1810.13292)

##### PDF
[http://arxiv.org/pdf/1810.13292](http://arxiv.org/pdf/1810.13292)

