---
layout: post
title: "Large-scale Image Geo-Localization Using Dominant Sets"
date: 2017-09-14 15:17:41
categories: arXiv_CV
tags: arXiv_CV
author: Eyasu Zemene, Yonatan Tariku, Haroon Idrees, Andrea Prati, Marcello Pelillo, Mubarak Shah
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a new approach for the challenging problem of geo-locating an image using image matching in a structured database of city-wide reference images with known GPS coordinates. We cast the geo-localization as a clustering problem on local image features. Akin to existing approaches on the problem, our framework builds on low-level features which allow partial matching between images. For each local feature in the query image, we find its approximate nearest neighbors in the reference set. Next, we cluster the features from reference images using Dominant Set clustering, which affords several advantages over existing approaches. First, it permits variable number of nodes in the cluster which we use to dynamically select the number of nearest neighbors (typically coming from multiple reference images) for each query feature based on its discrimination value. Second, as we also quantify in our experiments, this approach is several orders of magnitude faster than existing approaches. Thus, we obtain multiple clusters (different local maximizers) and obtain a robust final solution to the problem using multiple weak solutions through constrained Dominant Set clustering on global image features, where we enforce the constraint that the query image must be included in the cluster. This second level of clustering also bypasses heuristic approaches to voting and selecting the reference image that matches to the query. We evaluated the proposed framework on an existing dataset of 102k street view images as well as a new dataset of 300k images, and show that it outperforms the state-of-the-art by 20% and 7%, respectively, on the two datasets.

##### Abstract (translated by Google)
本文提出了一种新的方法，用于在具有已知的GPS坐标的城市参考图像的结构化数据库中使用图像匹配对图像进行地理定位的挑战性问题。我们将地理定位作为局部图像特征的聚类问题。类似于这个问题的现有方法，我们的框架建立在允许图像之间的部分匹配的低级特征上。对于查询图像中的每个局部特征，我们在参考集中找到其近似的近邻。接下来，我们使用Dominant Set聚类从参考图像中聚类特征，这提供了比现有方法更多的优点。首先，它允许可变数量的节点在我们用来动态选择最近的邻居（通常来自多个参考图像）为基础的每个查询特征的歧视值。其次，我们在实验中也进行了量化，这种方法比现有方法快几个数量级。因此，通过对全局图像特征进行约束优势集聚类，我们获得了多个聚类（不同的局部最大化），并使用多个弱解求解问题的最终解决方案，其中我们执行查询图像必须包含在聚类中的约束。第二级聚类还绕过启发式投票方式，选择与查询相匹配的参考图像。我们对102k街景图像的现有数据集以及300k图像的新数据集评估了所提出的框架，并且显示其在两个数据集上分别优于现有技术的20％和7％ 。

##### URL
[https://arxiv.org/abs/1702.01238](https://arxiv.org/abs/1702.01238)

##### PDF
[https://arxiv.org/pdf/1702.01238](https://arxiv.org/pdf/1702.01238)

