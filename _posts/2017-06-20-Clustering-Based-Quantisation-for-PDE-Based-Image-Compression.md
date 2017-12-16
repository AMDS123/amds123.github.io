---
layout: post
title: "Clustering-Based Quantisation for PDE-Based Image Compression"
date: 2017-06-20 10:02:05
categories: arXiv_CV
tags: arXiv_CV
author: Laurent Hoeltgen, Pascal Peter, Michael Breuß
mathjax: true
---

* content
{:toc}

##### Abstract
Finding optimal data for inpainting is a key problem in the context of partial differential equation based image compression. The data that yields the most accurate reconstruction is real-valued. Thus, quantisation models are mandatory to allow an efficient encoding. These can also be understood as challenging data clustering problems. Although clustering approaches are well suited for this kind of compression codecs, very few works actually consider them. Each pixel has a global impact on the reconstruction and optimal data locations are strongly correlated with their corresponding colour values. These facts make it hard to predict which feature works best. In this paper we discuss quantisation strategies based on popular methods such as k-means. We are lead to the central question which kind of feature vectors are best suited for image compression. To this end we consider choices such as the pixel values, the histogram or the colour map. Our findings show that the number of colours can be reduced significantly without impacting the reconstruction quality. Surprisingly, these benefits do not directly translate to a good image compression performance. The gains in the compression ratio are lost due to increased storage costs. This suggests that it is integral to evaluate the clustering on both, the reconstruction error and the final file size.

##### Abstract (translated by Google)
在基于偏微分方程的图像压缩方面，寻找最佳的修补数据是关键问题。产生最准确重建的数据是实值的。因此，量化模型是强制性的以允许有效的编码。这些也可以被理解为具有挑战性的数据聚类问题。虽然聚类方法非常适合这种压缩编解码器，但实际上很少有作品考虑它们。每个像素对重构具有全局影响，并且最佳数据位置与其对应的颜色值强相关。这些事实使得很难预测哪个功能效果最好。在本文中，我们讨论基于k-means等流行方法的量化策略。对于哪种特征矢量最适合于图像压缩，我们引出了一个中心问题。为此，我们考虑诸如像素值，直方图或颜色图的选择。我们的研究结果表明，颜色的数量可以显着减少而不影响重建质量。令人惊讶的是，这些好处并没有直接转化为良好的图像压缩性能。由于存储成本的增加，压缩比率的增加将会丢失。这表明，评估两者的聚类，重建错误和最终文件大小是不可或缺的。

##### URL
[https://arxiv.org/abs/1706.06347](https://arxiv.org/abs/1706.06347)

##### PDF
[https://arxiv.org/pdf/1706.06347](https://arxiv.org/pdf/1706.06347)

