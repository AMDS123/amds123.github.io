---
layout: post
title: "A propagation matting method based on the Local Sampling and KNN Classification with adaptive feature space"
date: 2016-05-03 02:09:22
categories: arXiv_CV
tags: arXiv_CV Classification Quantitative
author: Xiao Chen, Fazhi He
mathjax: true
---

* content
{:toc}

##### Abstract
Closed Form is a propagation based matting algorithm, functioning well on images with good propagation . The deficiency of the Closed Form method is that for complex areas with poor image propagation , such as hole areas or areas of long and narrow structures. The right results are usually hard to get. On these areas, if certain flags are provided, it can improve the effects of matting. In this paper, we design a matting algorithm by local sampling and the KNN classifier propagation based matting algorithm. First of all, build the corresponding features space according to the different components of image colors to reduce the influence of overlapping between the foreground and background, and to improve the classification accuracy of KNN classifier. Second, adaptively use local sampling or using local KNN classifier for processing based on the pros and cons of the sample performance of unknown image areas. Finally, based on different treatment methods for the unknown areas, we will use different weight for augmenting constraints to make the treatment more effective. In this paper, by combining qualitative observation and quantitative analysis, we will make evaluation of the experimental results through online standard set of evaluation tests. It shows that on images with good propagation , this method is as effective as the Closed Form method, while on images in complex regions, it can perform even better than Closed Form.

##### Abstract (translated by Google)
闭形式是基于传播的消光算法，在传播良好的图像上运行良好。闭式方法的不足之处在于对于图像传播较差的复杂区域，如孔洞面积或结构狭长的区域。正确的结果通常很难得到。在这些地方，如果提供某些标志，可以改善消光效果。在本文中，我们设计了一种基于局部采样的消光算法和基于KNN分类器传播的消光算法。首先根据图像颜色的不同成分构建相应的特征空间，以减少前景与背景重叠的影响，提高KNN分类器的分类精度。其次，基于未知图像区域的样本性能的优劣，自适应地使用局部采样或使用局部KNN分类器进行处理。最后，针对未知地区的不同治疗方法，我们将使用不同的权重来增加约束条件，使治疗效果更好。本文通过定性观测与定量分析相结合的方法，通过在线标准评价试验，对实验结果进行评价。它表明，在传播良好的图像上，这种方法与封闭式方法一样有效，而在复杂区域的图像上，它可以比封闭式表现更好。

##### URL
[https://arxiv.org/abs/1605.00732](https://arxiv.org/abs/1605.00732)

##### PDF
[https://arxiv.org/pdf/1605.00732](https://arxiv.org/pdf/1605.00732)

