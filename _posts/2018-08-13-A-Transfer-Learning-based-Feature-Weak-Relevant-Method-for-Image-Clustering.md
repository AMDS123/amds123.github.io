---
layout: post
title: "A Transfer Learning based Feature-Weak-Relevant Method for Image Clustering"
date: 2018-08-13 05:39:28
categories: arXiv_CV
tags: arXiv_CV Transfer_Learning Relation
author: Bo Dong, Xinnian Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Image clustering is to group a set of images into disjoint clusters in a way that images in the same cluster are more similar to each other than to those in other clusters, which is an unsupervised or semi-supervised learning process. It is a crucial and challenging task in machine learning and computer vision. The performances of existing image clustering methods have close relations with features used for clustering, even if unsupervised coding based methods have improved the performances a lot. To reduce the effect of clustering features, we propose a feature-weak-relevant method for image clustering. The proposed method converts an unsupervised clustering process into an alternative iterative process of unsupervised learning and transfer learning. The clustering process firstly starts up from handcrafted features based image clustering to estimate an initial label for every image, and secondly use a proposed sampling strategy to choose images with reliable labels to feed a transfer-learning model to learn representative features that can be used for next round of unsupervised learning. In this manner, image clustering is iteratively optimized. What's more, the handcrafted features are used to boot up the clustering process, and just have a little effect on the final performance; therefore, the proposed method is feature-weak-relevant. Experimental results on six kinds of public available datasets show that the proposed method outperforms state of the art methods and depends less on the employed features at the same time.

##### Abstract (translated by Google)
图像聚类是将一组图像分组为不相交的聚类，使得同一聚类中的图像彼此更相似，而不是其他聚类中的图像，这是无监督或半监督的学习过程。这是机器学习和计算机视觉中至关重要且具有挑战性的任务。现有图像聚类方法的性能与用于聚类的特征密切相关，即使基于无监督编码的方法已经大大提高了性能。为了减少聚类特征的影响，我们提出了一种与特征无关的图像聚类方法。所提出的方法将无监督聚类过程转换为无监督学习和转移学习的替代迭代过程。聚类过程首先从基于手工特征的图像聚类开始，以估计每个图像的初始标签，其次使用建议的采样策略来选择具有可靠标签的图像，以提供转移学习模型，以学习可用于下一轮无监督学习。以这种方式，迭代地优化图像聚类。更重要的是，手工制作的功能用于启动群集过程，并对最终性能产生一些影响;因此，所提出的方法与特征弱相关。对六种公共可用数据集的实验结果表明，该方法优于现有技术方法，同时较少依赖于所采用的特征。

##### URL
[http://arxiv.org/abs/1808.04068](http://arxiv.org/abs/1808.04068)

##### PDF
[http://arxiv.org/pdf/1808.04068](http://arxiv.org/pdf/1808.04068)

