---
layout: post
title: "Iterative Manifold Embedding Layer Learned by Incomplete Data for Large-scale Image Retrieval"
date: 2017-07-14 08:53:11
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Embedding
author: Jian Xu, Chunheng Wang, Chengzuo Qi, Cunzhao Shi, Baihua Xiao
mathjax: true
---

* content
{:toc}

##### Abstract
Existing manifold learning methods are not appropriate for image retrieval task, because most of them are unable to process query image and they have much additional computational cost especially for large scale database. Therefore, we propose the iterative manifold embedding (IME) layer, of which the weights are learned off-line by unsupervised strategy, to explore the intrinsic manifolds by incomplete data. On the large scale database that contains 27000 images, IME layer is more than 120 times faster than other manifold learning methods to embed the original representations at query time. We embed the original descriptors of database images which lie on manifold in a high dimensional space into manifold-based representations iteratively to generate the IME representations in off-line learning stage. According to the original descriptors and the IME representations of database images, we estimate the weights of IME layer by ridge regression. In on-line retrieval stage, we employ the IME layer to map the original representation of query image with ignorable time cost (2 milliseconds). We experiment on five public standard datasets for image retrieval. The proposed IME layer significantly outperforms related dimension reduction methods and manifold learning methods. Without post-processing, Our IME layer achieves a boost in performance of state-of-the-art image retrieval methods with post-processing on most datasets, and needs less computational cost.

##### Abstract (translated by Google)
现有的流形学习方法不适用于图像检索任务，因为其中大部分学习方法无法处理查询图像，特别是对于大规模数据库而言，它们有额外的计算成本。因此，我们提出了利用无监督策略离线学习权重的迭代流形嵌入（IME）层，利用不完全数据来研究内在流形。在包含27000个图像的大型数据库中，IME层比其他流形学习方法在查询时嵌入原始表示要快120倍以上。我们将位于高维空间流形上的数据库图像原始描述符迭代地嵌入到基于流形的表示中，以在脱机学习阶段生成IME表示。根据原始描述符和数据库图像的IME表示，我们通过岭回归来估计IME层的权重。在在线检索阶段，我们采用IME层将查询图像的原始表示与可忽略的时间成本（2毫秒）进行映射。我们在五个公共标准数据集上进行图像检索。所提出的IME层明显优于相关降维方法和多种学习方法。如果没有后期处理，我们的IME层可以提高最先进的图像检索方法的性能，对大多数数据集进行后期处理，而且需要更少的计算成本。

##### URL
[https://arxiv.org/abs/1707.09862](https://arxiv.org/abs/1707.09862)

##### PDF
[https://arxiv.org/pdf/1707.09862](https://arxiv.org/pdf/1707.09862)

