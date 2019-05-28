---
layout: post
title: "A New Clustering Method Based on Morphological Operations"
date: 2019-05-25 07:40:41
categories: arXiv_CV
tags: arXiv_CV
author: Zhenzhou Wang
mathjax: true
---

* content
{:toc}

##### Abstract
With the booming development of data science, many clustering methods have been proposed. All clustering methods have inherent merits and deficiencies. Therefore, they are only capable of clustering some specific types of data robustly. In addition, the accuracies of the clustering methods rely heavily on the characteristics of the data. In this paper, we propose a new clustering method based on the morphological operations. The morphological dilation is used to connect the data points based on their adjacency and form different connected domains. The iteration of the morphological dilation process stops when the number of connected domains equals the number of the clusters or when the maximum number of iteration is reached. The morphological dilation is then used to label the connected domains. The Euclidean distance between each data point and the points in each labeled connected domain is calculated. For each data point, there is a labeled connected domain that contains a point that yields the smallest Euclidean distance. The data point is assigned with the same labeling number as the labeled connected domain. We evaluate and compare the proposed method with state of the art clustering methods with different types of data. Experimental results show that the proposed method is more robust and generic for clustering two-dimensional or three-dimensional data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10548](http://arxiv.org/abs/1905.10548)

##### PDF
[http://arxiv.org/pdf/1905.10548](http://arxiv.org/pdf/1905.10548)

