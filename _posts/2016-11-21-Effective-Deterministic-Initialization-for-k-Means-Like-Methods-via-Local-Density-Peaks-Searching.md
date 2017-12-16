---
layout: post
title: "Effective Deterministic Initialization for $k$-Means-Like Methods via Local Density Peaks Searching"
date: 2016-11-21 13:26:37
categories: arXiv_CV
tags: arXiv_CV Face
author: Fengfu Li, Hong Qiao, Bo Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
The $k$-means clustering algorithm is popular but has the following main drawbacks: 1) the number of clusters, $k$, needs to be provided by the user in advance, 2) it can easily reach local minima with randomly selected initial centers, 3) it is sensitive to outliers, and 4) it can only deal with well separated hyperspherical clusters. In this paper, we propose a Local Density Peaks Searching (LDPS) initialization framework to address these issues. The LDPS framework includes two basic components: one of them is the local density that characterizes the density distribution of a data set, and the other is the local distinctiveness index (LDI) which we introduce to characterize how distinctive a data point is compared with its neighbors. Based on these two components, we search for the local density peaks which are characterized with high local densities and high LDIs to deal with 1) and 2). Moreover, we detect outliers characterized with low local densities but high LDIs, and exclude them out before clustering begins. Finally, we apply the LDPS initialization framework to $k$-medoids, which is a variant of $k$-means and chooses data samples as centers, with diverse similarity measures other than the Euclidean distance to fix the last drawback of $k$-means. Combining the LDPS initialization framework with $k$-means and $k$-medoids, we obtain two novel clustering methods called LDPS-means and LDPS-medoids, respectively. Experiments on synthetic data sets verify the effectiveness of the proposed methods, especially when the ground truth of the cluster number $k$ is large. Further, experiments on several real world data sets, Handwritten Pendigits, Coil-20, Coil-100 and Olivetti Face Database, illustrate that our methods give a superior performance than the analogous approaches on both estimating $k$ and unsupervised object categorization.

##### Abstract (translated by Google)
$ k $ -means聚类算法很流行，但有以下主要缺点：1）需要预先提供用户提供的聚类数$ k $，2）可以随机选择初始值中心，3）对异常值敏感，4）只能处理分离好的超球群。在本文中，我们提出了一个局部密度峰值搜索（LDPS）初始化框架来解决这些问题。 LDPS框架包括两个基本组成部分：其中一个是表征数据集密度分布的局部密度，另一个是我们引入的局部区别性指数（LDI），用于描述数据点与其邻居。基于这两个成分，我们寻找局部密度高，LDI高的局部密度峰值来处理1）和2）。此外，我们检测出局部密度较低但LDI较高的异常值，并在聚类开始之前将其排除。最后，我们将LDPS初始化框架应用于$ k $ -medoids，它是$ k $ -means的一个变体，并选择数据样本作为中心，除了欧几里德距离之外，还采用了各种相似性度量来修正$ k $的最后一个缺陷-手段。将LDPS初始化框架与$ k $ -means和$ k $ -medoids相结合，分别得到了两种新的聚类方法LDPS-means和LDPS-medoids。在合成数据集上的实验验证了所提出的方法的有效性，特别是当群集数$ k $的地面实况很大时。此外，在几个真实世界的数据集，手写Pendigits，线圈-20，线圈-100和Olivetti人脸数据库上的实验说明，我们的方法比类似的方法在估计$ k $和无监督对象分类方面提供了更好的性能。

##### URL
[https://arxiv.org/abs/1611.06777](https://arxiv.org/abs/1611.06777)

##### PDF
[https://arxiv.org/pdf/1611.06777](https://arxiv.org/pdf/1611.06777)

