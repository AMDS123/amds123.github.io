---
layout: post
title: "Sketch-based 3D Shape Retrieval using Convolutional Neural Networks"
date: 2015-04-14 11:55:45
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Attention CNN
author: Fang Wang, Le Kang, Yi Li
mathjax: true
---

* content
{:toc}

##### Abstract
Retrieving 3D models from 2D human sketches has received considerable attention in the areas of graphics, image retrieval, and computer vision. Almost always in state of the art approaches a large amount of "best views" are computed for 3D models, with the hope that the query sketch matches one of these 2D projections of 3D models using predefined features. We argue that this two stage approach (view selection -- matching) is pragmatic but also problematic because the "best views" are subjective and ambiguous, which makes the matching inputs obscure. This imprecise nature of matching further makes it challenging to choose features manually. Instead of relying on the elusive concept of "best views" and the hand-crafted features, we propose to define our views using a minimalism approach and learn features for both sketches and views. Specifically, we drastically reduce the number of views to only two predefined directions for the whole dataset. Then, we learn two Siamese Convolutional Neural Networks (CNNs), one for the views and one for the sketches. The loss function is defined on the within-domain as well as the cross-domain similarities. Our experiments on three benchmark datasets demonstrate that our method is significantly better than state of the art approaches, and outperforms them in all conventional metrics.

##### Abstract (translated by Google)
从2D人体草图中检索3D模型已经在图形，图像检索和计算机视觉领域受到相当的关注。几乎总是在最先进的方法中，为3D模型计算大量的“最佳视图”，希望查询草图使用预定义的特征匹配3D模型的这些2D投影之一。我们认为，这两个阶段的方法（视图选择 - 匹配）是实用的，但也是有问题的，因为“最佳视图”是主观的和模糊的，这使得匹配的输入变得模糊。这种不精确的匹配性质使得手动选择特征具有挑战性。我们不是依靠“最佳观点”和手工特征这个难以捉摸的概念，而是用极简主义的方法来定义我们的观点，并且学习草图和观点的特征。具体来说，我们大大减少了整个数据集只有两个预定义方向的视图数量。然后，我们学习两个连体卷积神经网络（CNN），一个用于观看，一个用于草图。损失函数是在域内定义的，以及跨域的相似性。我们在三个基准数据集上的实验表明，我们的方法明显优于现有技术的方法，并且在所有常规度量上都优于它们。

##### URL
[https://arxiv.org/abs/1504.03504](https://arxiv.org/abs/1504.03504)

##### PDF
[https://arxiv.org/pdf/1504.03504](https://arxiv.org/pdf/1504.03504)

