---
layout: post
title: "Adaptive Nonparametric Image Parsing"
date: 2015-05-07 02:28:32
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Tam V. Nguyen, Canyi Lu, Jose Sepulveda, Shuicheng Yan
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present an adaptive nonparametric solution to the image parsing task, namely annotating each image pixel with its corresponding category label. For a given test image, first, a locality-aware retrieval set is extracted from the training data based on super-pixel matching similarities, which are augmented with feature extraction for better differentiation of local super-pixels. Then, the category of each super-pixel is initialized by the majority vote of the $k$-nearest-neighbor super-pixels in the retrieval set. Instead of fixing $k$ as in traditional non-parametric approaches, here we propose a novel adaptive nonparametric approach which determines the sample-specific k for each test image. In particular, $k$ is adaptively set to be the number of the fewest nearest super-pixels which the images in the retrieval set can use to get the best category prediction. Finally, the initial super-pixel labels are further refined by contextual smoothing. Extensive experiments on challenging datasets demonstrate the superiority of the new solution over other state-of-the-art nonparametric solutions.

##### Abstract (translated by Google)
在本文中，我们提出了一个自适应非参数解决方案的图像解析任务，即注释每个图像像素与其相应的类别标签。对于一个给定的测试图像，首先根据超像素匹配相似度从训练数据中提取一个局部感知的检索集，这些相似度用特征提取来增强，以便更好地区分局部超像素。然后，通过检索集中$ k $  - 最近邻居超像素的多数投票来初始化每个超像素的类别。在传统的非参数方法中，我们没有固定$ k $，而是提出了一种新的自适应非参数方法，它可以确定每个测试图像的样本特定k值。特别地，$ k $被自适应地设置为检索集中的图像可以用来获得最佳类别预测的最少的最接近的超像素的数量。最后，通过上下文平滑对最初的超像素标签进一步细化。对具有挑战性的数据集进行大量的实验证明，新解决方案优于其他最先进的非参数解决方案。

##### URL
[https://arxiv.org/abs/1505.01560](https://arxiv.org/abs/1505.01560)

##### PDF
[https://arxiv.org/pdf/1505.01560](https://arxiv.org/pdf/1505.01560)

