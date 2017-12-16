---
layout: post
title: "An evaluation of large-scale methods for image instance and class discovery"
date: 2017-08-09 16:29:21
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Matthijs Douze, Hervé Jégou, Jeff Johnson
mathjax: true
---

* content
{:toc}

##### Abstract
This paper aims at discovering meaningful subsets of related images from large image collections without annotations. We search groups of images related at different levels of semantic, i.e., either instances or visual classes. While k-means is usually considered as the gold standard for this task, we evaluate and show the interest of diffusion methods that have been neglected by the state of the art, such as the Markov Clustering algorithm. We report results on the ImageNet and the Paris500k instance dataset, both enlarged with images from YFCC100M. We evaluate our methods with a labelling cost that reflects how much effort a human would require to correct the generated clusters. Our analysis highlights several properties. First, when powered with an efficient GPU implementation, the cost of the discovery process is small compared to computing the image descriptors, even for collections as large as 100 million images. Second, we show that descriptions selected for instance search improve the discovery of object classes. Third, the Markov Clustering technique consistently outperforms other methods; to our knowledge it has never been considered in this large scale scenario.

##### Abstract (translated by Google)
本文旨在从没有注释的大型图像集合中发现有意义的相关图像子集。我们搜索不同级别的语义相关的图像组，即实例或视觉类。虽然k-means通常被认为是这个任务的黄金标准，但是我们评估并显示了被现有技术忽略的扩散方法的兴趣，例如马尔科夫聚类算法。我们在ImageNet和Paris500k实例数据集上报告结果，这两个数据集都放大了来自YFCC100M的图像。我们用标签成本来评估我们的方法，该成本反映了人类需要多少努力才能纠正生成的聚类。我们的分析强调了几个属性首先，当使用高效的GPU实现时，与计算图像描述符相比，发现过程的成本较低，即使对于1亿个图像的集合也是如此。其次，我们展示为实例搜索选择的描述改进了对象类的发现。第三，马尔可夫聚类技术一贯优于其他方法;据我们所知，在这个大规模的情况下从未被考虑过。

##### URL
[https://arxiv.org/abs/1708.02898](https://arxiv.org/abs/1708.02898)

##### PDF
[https://arxiv.org/pdf/1708.02898](https://arxiv.org/pdf/1708.02898)

