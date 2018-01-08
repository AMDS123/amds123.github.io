---
layout: post
title: "Adaptive kNN using Expected Accuracy for Classification of Geo-Spatial Data"
date: 2017-12-14 14:09:06
categories: arXiv_CV
tags: arXiv_CV Classification
author: Mark Kibanov, Martin Becker, Juergen Mueller, Martin Atzmueller, Andreas Hotho, Gerd Stumme
mathjax: true
---

* content
{:toc}

##### Abstract
The k-Nearest Neighbor (kNN) classification approach is conceptually simple - yet widely applied since it often performs well in practical applications. However, using a global constant k does not always provide an optimal solution, e.g., for datasets with an irregular density distribution of data points. This paper proposes an adaptive kNN classifier where k is chosen dynamically for each instance (point) to be classified, such that the expected accuracy of classification is maximized. We define the expected accuracy as the accuracy of a set of structurally similar observations. An arbitrary similarity function can be used to find these observations. We introduce and evaluate different similarity functions. For the evaluation, we use five different classification tasks based on geo-spatial data. Each classification task consists of (tens of) thousands of items. We demonstrate, that the presented expected accuracy measures can be a good estimator for kNN performance, and the proposed adaptive kNN classifier outperforms common kNN and previously introduced adaptive kNN algorithms. Also, we show that the range of considered k can be significantly reduced to speed up the algorithm without negative influence on classification accuracy.

##### Abstract (translated by Google)
k-最近邻（kNN）分类方法在概念上是简单的 - 但由于其在实际应用中经常表现良好而被广泛应用。然而，使用全局常数k并不总是提供最佳解决方案，例如，对于数据点具有不规则密度分布的数据集。本文提出了一种自适应kNN分类器，其中对每个要分类的实例（点）动态选择k，使得分类的预期准确度最大化。我们将预期的准确度定义为一组结构相似的观测值的准确度。可以使用任意相似度函数来查找这些观察值。我们介绍和评估不同的相似性功能。为了评估，我们使用基于地理空间数据的五个不同的分类任务。每个分类任务由（数十个）数千个项目组成。我们证明，所提出的期望的精度测量可以是kNN性能的一个好的估计量，并且所提出的自适应kNN分类器优于普通的kNN和先前引入的自适应kNN算法。此外，我们表明，考虑k的范围可以显着减少，加快算法没有负面影响的分类精度。

##### URL
[http://arxiv.org/abs/1801.01453](http://arxiv.org/abs/1801.01453)

##### PDF
[http://arxiv.org/pdf/1801.01453](http://arxiv.org/pdf/1801.01453)

