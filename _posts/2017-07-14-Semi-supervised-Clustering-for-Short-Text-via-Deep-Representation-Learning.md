---
layout: post
title: "Semi-supervised Clustering for Short Text via Deep Representation Learning"
date: 2017-07-14 19:52:33
categories: arXiv_SD
tags: arXiv_SD Represenation_Learning
author: Zhiguo Wang, Haitao Mi, Abraham Ittycheriah
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose a semi-supervised method for short text clustering, where we represent texts as distributed vectors with neural networks, and use a small amount of labeled data to specify our intention for clustering. We design a novel objective to combine the representation learning process and the k-means clustering process together, and optimize the objective with both labeled data and unlabeled data iteratively until convergence through three steps: (1) assign each short text to its nearest centroid based on its representation from the current neural networks; (2) re-estimate the cluster centroids based on cluster assignments from step (1); (3) update neural networks according to the objective by keeping centroids and cluster assignments fixed. Experimental results on four datasets show that our method works significantly better than several other text clustering methods.

##### Abstract (translated by Google)
在这项工作中，我们提出了一种半监督的短文本聚类方法，其中我们将文本表示为带有神经网络的分布式矢量，并使用少量的标记数据来指定我们的聚类意图。我们设计了一个新的目标，把表示学习过程和k-均值聚类过程结合在一起，并且用标记数据和无标记数据迭代地优化目标，直到收敛通过三个步骤：（1）将每个短文本分配到其最接近的质心从目前的神经网络的代表; （2）根据步骤（1）的聚类分配重新估计聚类质心; （3）通过保持质心和聚类分配的固定来根据目标更新神经网络。在四个数据集上的实验结果表明，我们的方法比其他几种文本聚类方法显着地好。

##### URL
[https://arxiv.org/abs/1602.06797](https://arxiv.org/abs/1602.06797)

##### PDF
[https://arxiv.org/pdf/1602.06797](https://arxiv.org/pdf/1602.06797)

