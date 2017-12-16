---
layout: post
title: "Iterative Spectral Clustering for Unsupervised Object Localization"
date: 2017-06-29 12:37:44
categories: arXiv_CV
tags: arXiv_CV Weakly_Supervised
author: Aditya Vora, Shanmuganathan Raman
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of unsupervised object localization in an image. Unlike previous supervised and weakly supervised algorithms that require bounding box or image level annotations for training classifiers in order to learn features representing the object, we propose a simple yet effective technique for localization using iterative spectral clustering. This iterative spectral clustering approach along with appropriate cluster selection strategy in each iteration naturally helps in searching of object region in the image. In order to estimate the final localization window, we group the proposals obtained from the iterative spectral clustering step based on the perceptual similarity, and average the coordinates of the proposals from the top scoring groups. We benchmark our algorithm on challenging datasets like Object Discovery and PASCAL VOC 2007, achieving an average CorLoc percentage of 51% and 35% respectively which is comparable to various other weakly supervised algorithms despite being completely unsupervised.

##### Abstract (translated by Google)
本文介绍了图像中无监督对象定位的问题。与以前的监督和弱监督算法不同，为了学习代表对象的特征，我们提出了一种简单而有效的迭代谱聚类定位技术。这种迭代谱聚类方法以及在每次迭代中适当的聚类选择策略自然有助于在图像中搜索物体区域。为了估计最终的定位窗口，我们根据感知相似性对从迭代谱聚类步骤获得的提议进行分组，并且将来自最高得分组的提议的坐标平均化。我们将基于对象发现和PASCAL VOC 2007等具有挑战性的数据集的算法进行基准测试，平均CorLoc百分比分别为51％和35％，与其他各种弱监督算法相比，尽管完全没有监督。

##### URL
[https://arxiv.org/abs/1706.09719](https://arxiv.org/abs/1706.09719)

##### PDF
[https://arxiv.org/pdf/1706.09719](https://arxiv.org/pdf/1706.09719)

