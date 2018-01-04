---
layout: post
title: "A Novel Feature Descriptor for Image Retrieval by Combining Modified Color Histogram and Diagonally Symmetric Co-occurrence Texture Pattern"
date: 2018-01-03 01:39:05
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Relation
author: Ayan Kumar Bhunia, Avirup Bhattacharyya, Prithaj Banerjee, Partha Pratim Roy, Subrahmanyam Murala
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we have proposed a novel feature descriptors combining color and texture information collectively. In our proposed color descriptor component, the inter-channel relationship between Hue (H) and Saturation (S) channels in the HSV color space has been explored which was not done earlier. We have quantized the H channel into a number of bins and performed the voting with saturation values and vice versa by following a principle similar to that of the HOG descriptor, where orientation of the gradient is quantized into a certain number of bins and voting is done with gradient magnitude. This helps us to study the nature of variation of saturation with variation in Hue and nature of variation of Hue with the variation in saturation. The texture component of our descriptor considers the co-occurrence relationship between the pixels symmetric about both the diagonals of a 3x3 window. Our work is inspired from the work done by Dubey et al.[1]. These two components, viz. color and texture information individually perform better than existing texture and color descriptors. Moreover, when concatenated the proposed descriptors provide significant improvement over existing descriptors for content base color image retrieval. The proposed descriptor has been tested for image retrieval on five databases, including texture image databases - MIT VisTex database and Salzburg texture database and natural scene databases Corel 1K, Corel 5K and Corel 10K. The precision and recall values experimented on these databases are compared with some state-of-art local patterns. The proposed method provided satisfactory results from the experiments.

##### Abstract (translated by Google)
在本文中，我们已经提出了一个新的特征描述符集合颜色和纹理信息。在我们提出的颜色描述符组件中，HSV颜色空间中Hue（H）和Saturation（S）通道之间的通道间关系已经被探索，这在以前没有做过。我们已经将H通道量化为多个分箱，并且通过遵循类似于HOG描述符的原理来执行具有饱和度值的投票，反之亦然，其中梯度的方向量化为一定数量的分箱并且完成投票与梯度幅度。这有助于我们研究饱和度变化的性质，色调的变化和色调的变化性质随着饱和度的变化而变化。我们描述符的纹理分量考虑了关于3×3窗口的对角线对称的像素之间的共现关系。我们的工作受到了Dubey等[1]所做的工作的启发。这两个组件，即。颜色和纹理信息单独执行比现有纹理和颜色描述符更好。而且，当连接时，所提出的描述符相对于用于内容基础彩色图像检索的现有描述符提供显着的改进。所提出的描述符已经在五个数据库上进行了图像检索，包括纹理图像数据库-MIT VisTex数据库和萨尔茨堡纹理数据库以及自然场景数据库Corel 1K，Corel 5K和Corel 10K。在这些数据库上实验的精度和召回值与一些最新的本地模式进行比较。该方法提供了令人满意的实验结果。

##### URL
[http://arxiv.org/abs/1801.00879](http://arxiv.org/abs/1801.00879)

##### PDF
[http://arxiv.org/pdf/1801.00879](http://arxiv.org/pdf/1801.00879)

