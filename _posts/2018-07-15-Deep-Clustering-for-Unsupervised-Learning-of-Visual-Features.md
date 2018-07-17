---
layout: post
title: "Deep Clustering for Unsupervised Learning of Visual Features"
date: 2018-07-15 09:41:39
categories: arXiv_CV
tags: arXiv_CV CNN
author: Mathilde Caron, Piotr Bojanowski, Armand Joulin, Matthijs Douze
mathjax: true
---

* content
{:toc}

##### Abstract
Clustering is a class of unsupervised learning methods that has been extensively applied and studied in computer vision. Little work has been done to adapt it to the end-to-end training of visual features on large scale datasets. In this work, we present DeepCluster, a clustering method that jointly learns the parameters of a neural network and the cluster assignments of the resulting features. DeepCluster iteratively groups the features with a standard clustering algorithm, k-means, and uses the subsequent assignments as supervision to update the weights of the network. We apply DeepCluster to the unsupervised training of convolutional neural networks on large datasets like ImageNet and YFCC100M. The resulting model outperforms the current state of the art by a significant margin on all the standard benchmarks.

##### Abstract (translated by Google)
聚类是一类无监督学习方法，已在计算机视觉中得到广泛应用和研究。很少有工作使其适应大规模数据集上的视觉特征的端到端培训。在这项工作中，我们提出了一种聚类方法DeepCluster，它共同学习神经网络的参数和结果特征的聚类分配。 DeepCluster使用标准聚类算法k-means迭代地对特征进行分组，并使用后续分配作为监督来更新网络的权重。我们将DeepCluster应用于ImageNet和YFCC100M等大型数据集上的无控制卷积神经网络训练。由此产生的模型在所有标准基准测试中均大大优于现有技术水平。

##### URL
[http://arxiv.org/abs/1807.05520](http://arxiv.org/abs/1807.05520)

##### PDF
[http://arxiv.org/pdf/1807.05520](http://arxiv.org/pdf/1807.05520)

